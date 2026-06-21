---
layout: default
---

<div style="margin-bottom: 3rem; margin-top: 1rem;">
  <img src="{{ '/assets/image/logo.jpeg' | relative_url }}" alt="Logo dello Studio" style="width: 100%; height: auto; display: block;">
</div>

Benvenuti nel nostro spazio esclusivo dedicato alla cura del corpo, all'equilibrio e al movimento consapevole. Lontano dai ritmi frenetici, il nostro approccio si concentra sulla precisione, sul recupero funzionale e sul benessere profondo, sempre guidato da istruttrici certificate.

---

## 🧘‍♀️ Il Nostro Team: Istruttrici Certificate
La qualità del tuo movimento è la nostra priorità. Tutte le lezioni sono condotte esclusivamente da **istruttrici altamente qualificate e certificate**. Il nostro team ti seguirà passo dopo passo, correggendo la postura e adattando l'intensità e la dinamica degli esercizi alle tue specifiche esigenze fisiche.

---

<div id="percorsi" style="scroll-margin-top: 100px;"></div>

## 🌿 I Nostri Percorsi

* **Pilates Reformer:** Lavoro sul macchinario per un allenamento di resistenza fluido. Ideale per riallineare la colonna e rinforzare il baricentro senza impatti sulle articolazioni.
* **Pilates Matwork:** Esercizi a corpo libero per sviluppare controllo, flessibilità e piena consapevolezza del proprio corpo.
* **Rieducazione del Movimento:** Sessioni mirate per ripristinare la corretta architettura posturale, sciogliere le tensioni muscolari e prevenire fastidi e infortuni.

---

<div id="prenota" style="scroll-margin-top: 100px;"></div>

## 📅 Prenota la tua Lezione

Scegli la tipologia di lezione per visualizzare i giorni e gli orari disponibili:

<!-- Toggle Switch -->
<div style="display: flex; align-items: center; justify-content: center; gap: 15px; margin-bottom: 30px; margin-top: 10px; font-family: 'Montserrat', sans-serif;">
  <label for="calendar-toggle" id="label-privata" style="font-weight: 600; color: #D2B4B4; cursor: pointer; font-size: 0.95rem;">
    👤 Privata (40€)
  </label>
  
  <label for="calendar-toggle" style="position: relative; display: inline-block; width: 60px; height: 34px; cursor: pointer; flex-shrink: 0;">
    <input type="checkbox" id="calendar-toggle" onchange="toggleCalendar()" style="opacity: 0; width: 0; height: 0; position: absolute;">
    <span id="toggle-bg" style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; background-color: #D2B4B4; border-radius: 34px; transition: .4s;"></span>
    <span id="toggle-slider" style="position: absolute; height: 26px; width: 26px; left: 4px; bottom: 4px; background-color: white; border-radius: 50%; transition: .4s; box-shadow: 0 2px 4px rgba(0,0,0,0.2);"></span>
  </label>

  <label for="calendar-toggle" id="label-condivisa" style="font-weight: 600; color: #4A4A4A; cursor: pointer; font-size: 0.95rem;">
    👥 Condivisa (20€)
  </label>
</div>

<!-- Contenitore Iframe Privata (Visibile di default) -->
<div id="div-privata" style="width: 100%; height: 600px; -webkit-overflow-scrolling: touch; overflow-y: auto;">
  <iframe src="https://cal.com/studio-360-pilates-n0s257/privata?embed=booking" style="width: 100%; height: 100%; border: none;"></iframe>
</div>

<!-- Contenitore Iframe Condivisa (Nascosto di default) -->
<div id="div-condivisa" style="width: 100%; height: 600px; display: none; -webkit-overflow-scrolling: touch; overflow-y: auto;">
  <iframe src="https://cal.com/studio-360-pilates-n0s257/condivisa?embed=booking" style="width: 100%; height: 100%; border: none;"></iframe>
</div>

<script type="text/javascript">
  function toggleCalendar() {
    const isCondivisa = document.getElementById('calendar-toggle').checked;
    const divPrivata = document.getElementById('div-privata');
    const divCondivisa = document.getElementById('div-condivisa');
    const labelPrivata = document.getElementById('label-privata');
    const labelCondivisa = document.getElementById('label-condivisa');
    const slider = document.getElementById('toggle-slider');

    if (!isCondivisa) {
      // Toggle a sinistra (Lezione Privata)
      divPrivata.style.display = "block";
      divCondivisa.style.display = "none";
      
      labelPrivata.style.color = "#D2B4B4"; // Rosa antico
      labelCondivisa.style.color = "#4A4A4A"; // Grigio scuro
      
      slider.style.transform = "translateX(0)";
    } else {
      // Toggle a destra (Lezione Condivisa)
      divPrivata.style.display = "none";
      divCondivisa.style.display = "block";
      
      labelPrivata.style.color = "#4A4A4A"; // Grigio scuro
      labelCondivisa.style.color = "#D2B4B4"; // Rosa antico
      
      slider.style.transform = "translateX(26px)";
    }
  }
</script>

---

<div id="prezzi" style="scroll-margin-top: 100px;"></div>

## 💳 Pacchetti e Promozioni

Offriamo diverse soluzioni pensate per dare continuità al tuo percorso di benessere:
* **Lezione Singola:** Perfetta per provare il nostro metodo o per chi ha impegni lavorativi variabili (40€ Privata / 20€ Condivisa).
* **Pacchetto 10 Lezioni (300€):** La scelta ideale per impostare un lavoro costante nel tempo. Il pacchetto richiede il **pagamento anticipato** in un'unica soluzione tramite la nostra segreteria, garantendoti la massima comodità organizzativa per le prenotazioni future.

---

<div id="info" style="scroll-margin-top: 100px;"></div>

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
