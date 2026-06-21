---
layout: default
---

<div style="text-align: center; margin-bottom: 2rem;">
  <img src="{{ '/assets/image/logo.jepg' | relative_url }}" alt="Studio 360 Pilates Logo" style="max-width: 220px; height: auto; border-radius: 8px;">
</div>

# Studio 360 Pilates
**Matwork | Reformer | Rieducazione del Movimento a Ladispoli**

Benvenuti in **Studio 360 Pilates**. Uno spazio esclusivo dedicato alla cura del corpo, all'equilibrio e al movimento consapevole. Lontano dai ritmi frenetici, il nostro approccio si concentra sulla precisione, sul recupero funzionale e sul benessere profondo, sempre guidato da istruttrici certificate.

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

<div id="div-privata" style="width: 100%; height: 600px; -webkit-overflow-scrolling: touch; overflow-y: auto;">
  <iframe src="https://cal.com/studio-360-pilates-n0s257/privata?embed=booking" style="width: 100%; height: 100%; border: none;"></iframe>
</div>

<div id="div-condivisa" style="width: 100%; height: 600px; display: none; -webkit-overflow-scrolling: touch; overflow-y: auto;">
  <iframe src="https://cal.com/studio-360-pilates-n0s257/condivisa?embed=booking" style="width: 100%; height: 100%; border: none;"></iframe>
</div>

<script type="text/javascript">
  function switchCalendar(type) {
    const btnPrivata = document.getElementById('btn-privata');
    const btnCondivisa = document.getElementById('btn-condivisa');
    const divPrivata = document.getElementById('div-privata');
    const divCondivisa = document.getElementById('div-condivisa');

    if (type === 'privata') {
      // Mostra Privata, Nascondi Condivisa
      divPrivata.style.display = "block";
      divCondivisa.style.display = "none";
      
      // Colora bottone Privata (Rosa Antico)
      btnPrivata.style.backgroundColor = "#D2B4B4";
      btnPrivata.style.color = "white";
      
      // Spegni bottone Condivisa (Grigio Perla)
      btnCondivisa.style.backgroundColor = "#E2E4E6";
      btnCondivisa.style.color = "#4A4A4A";
    } else {
      // Mostra Condivisa, Nascondi Privata
      divPrivata.style.display = "none";
      divCondivisa.style.display = "block";
      
      // Colora bottone Condivisa (Rosa Antico)
      btnCondivisa.style.backgroundColor = "#D2B4B4";
      btnCondivisa.style.color = "white";
      
      // Spegni bottone Privata (Grigio Perla)
      btnPrivata.style.backgroundColor = "#E2E4E6";
      btnPrivata.style.color = "#4A4A4A";
    }
  }
</script>

---

## 💳 Pacchetti e Promozioni

Offriamo diverse soluzioni pensate per dare continuità al tuo percorso di benessere:
* **Lezione Singola:** Perfetta per provare il nostro metodo o per chi ha impegni lavorativi variabili (40€ Privata / 20€ Condivisa).
* **Pacchetto 10 Lezioni (300€):** La scelta ideale per impostare un lavoro costante nel tempo. Il pacchetto richiede il **pagamento anticipato** in un'unica soluzione tramite la nostra segreteria, garantendoti la massima comodità organizzativa per le prenotazioni future.

---

## 📌 Info e Regolamento

Per mantenere un ambiente sereno e garantire un servizio di altissima qualità, ti preghiamo di leggere le nostre linee guida:

1.  **Costi e Prenotazioni:** La prenotazione tramite il calendario blocca ufficialmente il tuo posto in sala. Il saldo della lezione (40€ o 20€ in base al percorso scelto) o l'acquisto del pacchetto verrà gestito tramite la segreteria.
2.  **Certificato Medico:** Per la tua sicurezza e nel rispetto delle normative vigenti, è obbligatorio inviarci copia del *Certificato Medico per attività sportiva non agonistica* in corso di validità prima di accedere in sala per la prima volta.
3.  **Politica di Cancellazione:** Le lezioni possono essere disdette o riprogrammate senza alcuna penale con almeno **24 ore di preavviso**. Oltre questo termine, per rispetto del lavoro delle nostre istruttrici e degli altri soci, la sessione verrà interamente addebitata o decurtata dal pacchetto attivo.

---

## ❓ Domande Frequenti (FAQ)

**Cosa devo indossare per la lezione?**
Consigliamo un abbigliamento comodo e preferibilmente aderente, per permettere alle istruttrici di controllare l'allineamento della colonna e delle articolazioni. È richiesto l'uso di calzini antiscivolo (disponibili anche in studio) e di un asciugamano personale.

**Non ho mai fatto Pilates, posso partecipare lo stesso?**
Assolutamente sì. Il nostro approccio non è "da palestra", ma orientato alla cura e alla rieducazione del movimento. Essendo seguiti da professioniste certificate, il lavoro verrà cucito su misura in base al tuo livello di partenza.

---

## 📍 Contatti

Siamo a **Ladispoli (RM)**.
Hai dubbi su quale sia il percorso più adatto a te o desideri maggiori informazioni?

* 📱 **[Scrivici su WhatsApp](https://wa.me/39INSERISCI_TUO_NUMERO)**
* 📸 **Seguici su Instagram:** [@studio360pilates](#)
