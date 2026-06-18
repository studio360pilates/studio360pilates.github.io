---
layout: default
---

# Studio 360 Pilates
**Matwork | Reformer | Rieducazione del Movimento a Ladispoli**

Benvenuti in **Studio 360 Pilates**. Uno spazio esclusivo dedicato alla cura del corpo, all'equilibrio e al movimento consapevole. Lontano dai ritmi frenetici, il nostro approccio si concentra sulla precisione, sul recupero funzionale e sempre guidato da istruttrici certificate.

---

## 🧘‍♀️ Il Nostro Team: Istruttrici Certificate
La qualità del tuo movimento è la nostra priorità. Tutte le lezioni sono condotte esclusivamente da **istruttrici altamente qualificate e certificate**. Il nostro team ti seguirà passo dopo passo, correggendo la postura e adattando l'intensità e la dinamica degli esercizi alle tue specifiche esigenze fisiche.

---

## 🌿 I Nostri Percorsi

* **Pilates Reformer:** Lavoro sul macchinario per un allenamento di resistenza fluido. Ideale per riallineare la colonna e rinforzare il baricentro senza impatti sulle articolazioni.
* **Pilates Matwork:** Esercizi a corpo libero per sviluppare controllo, flessibilità e piena consapevolezza del proprio corpo.
* **Rieducazione del Movimento:** Sessioni mirate per ripristinare la corretta architettura posturale, sciogliere le tensioni muscolari e prevenire fastidi e infortuni.

---

## 📅 Prenota la tua Lezione

Scegli la tipologia di lezione per visualizzare i giorni e gli orari disponibili:

<div style="display: flex; gap: 10px; margin-bottom: 20px; width: 100%;">
  <button id="btn-privata" onclick="switchCalendar('privata')" style="flex: 1; padding: 12px; font-family: 'Montserrat', sans-serif; font-weight: 600; border: 1px solid #D1D4D6; border-radius: 6px; cursor: pointer; background-color: #D2B4B4; color: white; transition: all 0.3s;">
    👤 Lezione Privata (40€)
  </button>
  <button id="btn-condivisa" onclick="switchCalendar('condivisa')" style="flex: 1; padding: 12px; font-family: 'Montserrat', sans-serif; font-weight: 600; border: 1px solid #D1D4D6; border-radius: 6px; cursor: pointer; background-color: #E2E4E6; color: #4A4A4A; transition: all 0.3s;">
    👥 Lezione Condivisa (20€)
  </button>
</div>

<div style="width:100%; height:600px; overflow:scroll;" id="my-cal-inline"></div>

<script type="text/javascript">
  // Script di inizializzazione nativo Cal.com
  (function (C, A, L) { let p = function (a, ar) { a.q.push(ar); }; let d = C.document; C.Cal = C.Cal || function () { let cal = C.Cal; let ar = arguments; if (!cal.loaded) { cal.ns = {}; cal.q = cal.q || []; d.head.appendChild(d.createElement("script")).src = A; cal.loaded = true; } if (ar[0] === L) { const api = function () { p(api, arguments); }; const namespace = ar[1]; api.q = api.q || []; if(typeof namespace === "string"){cal.ns[namespace] = cal.ns[namespace] || api;p(cal.ns[namespace], ar);p(cal, ["initNamespace", namespace]);} else p(cal, ar); return;} p(cal, ar); }; })(window, "https://app.cal.com/embed/embed.js", "init");
  
  Cal("init", "booking", {origin:"https://app.cal.com"});
  Cal.config = Cal.config || {};
  Cal.config.forwardQueryParams = true;

  // Funzione dinamica per cambiare calendario e stile dei bottoni
  function switchCalendar(type) {
    const btnPrivata = document.getElementById('btn-privata');
    const btnCondivisa = document.getElementById('btn-condivisa');
    let targetLink = "";

    if (type === 'privata') {
      targetLink = "studio-360-pilates-n0s257/50min";
      // Stile attivo per Privata (Rosa Antico)
      btnPrivata.style.backgroundColor = "#D2B4B4";
      btnPrivata.style.color = "white";
      // Stile inattivo per Condivisa (Grigio Perla)
      btnCondivisa.style.backgroundColor = "#E2E4E6";
      btnCondivisa.style.color = "#4A4A4A";
    } else {
      // Sostituisci qui sotto con lo slug esatto del tuo secondo evento da 20€ su cal.com
      targetLink = "studio-360-pilates-n0s257/condivisa"; 
      // Stile attivo per Condivisa (Rosa Antico)
      btnCondivisa.style.backgroundColor = "#D2B4B4";
      btnCondivisa.style.color = "white";
      // Stile inattivo per Privata (Grigio Perla)
      btnPrivata.style.backgroundColor = "#E2E4E6";
      btnPrivata.style.color = "#4A4A4A";
    }

    // Carica il calendario corretto nel contenitore
    Cal.ns["booking"]("inline", {
      elementOrSelector: "#my-cal-inline",
      config: {"layout": "month_view", "useSlotsViewOnSmallScreen": "true"},
      calLink: targetLink,
    });

    Cal.ns["booking"]("ui", {
      "cssVarsPerTheme": {
        "light": {"cal-brand": "#D2B4B4"},
        "dark": {"cal-brand": "#D2B4B4"}
      },
      "hideEventTypeDetails": false,
      "layout": "month_view"
    });
  }

  // Avvia la pagina mostrando di default la Lezione Privata
  switchCalendar('privata');
</script>

---

## 💳 Pacchetti e Promozioni

Offriamo diverse soluzioni pensate per dare continuità al tuo percorso di benessere:
* **Lezione Singola:** Perfetta per provare il nostro metodo o per chi ha impegni variabili.
* **Pacchetti da 5 o 10 Lezioni:** La scelta ideale per impostare un lavoro costante nel tempo. I pacchetti prevedono il saldo anticipato in un'unica soluzione tramite la bacheca del nostro studio.

---

## 📌 Info e Regolamento

Per mantenere un ambiente sereno e garantire un servizio di altissima qualità, ti preghiamo di leggere le nostre linee guida:

1.  **Pagamento Anticipato:** Per ottimizzare la gestione dei posti in sala (limitati sui macchinari), la prenotazione si intende confermata esclusivamente al completamento del pagamento online sicuro tramite carta di credito sul nostro portale.
2.  **Certificato Medico:** Per la tua sicurezza e nel rispetto delle normative vigenti, è obbligatorio inviarci copia del *Certificato Medico per attività sportiva non agonistica* prima di accedere in sala per la prima volta.
3.  **Politica di Cancellazione:** Le lezioni possono essere disdette o riprogrammate senza alcuna penale con almeno **24 ore di preavviso**. Oltre questo termine, la sessione verrà interamente addebitata.

---

## ❓ Domande Frequenti (FAQ)

**Cosa devo indossare per la lezione?**
Consigliamo un abbigliamento comodo e preferibilmente aderente, per permettere alle istruttrici di controllare l'allineamento della colonna e delle articolazioni. È richiesto l'uso di calzini antiscivolo e di un asciugamano personale.

**Non ho mai fatto Pilates, posso partecipare lo stesso?**
Assolutamente sì. Il nostro approccio è orientato alla cura e alla rieducazione del movimento. Essendo seguiti da professioniste certificate, il lavoro verrà cucito su misura in base al tuo livello di partenza.

---

## 📍 Contatti

Siamo a **Ladispoli (RM)**.
Hai dubbi su quale sia il percorso più adatto a te o desideri ricevere il nostro listino prezzi?

* 📱 **[Scrivici su WhatsApp](https://wa.me/39INSERISCI_TUO_NUMERO)**
* 📸 **Seguici su Instagram:** [@studio360pilates](#)
