MILU LUXURY APARTMENT — SITO WEB
=================================

CONTENUTO DELLA CARTELLA
  index.html            il sito completo (italiano + inglese)
  foto/                 le 25 immagini
  disponibilita.json    le date da bloccare sul calendario

COME VEDERLO
  Doppio clic su index.html. Le tre voci devono restare sempre
  nella stessa cartella, altrimenti le foto non si vedono.


CALENDARIO E PREZZI
-------------------
Il calendario calcola il prezzo da solo:

  1 – 3 ospiti     56 € bassa stagione   58 € alta stagione
  4 ospiti         46 €                  49 €
  5 – 6 ospiti     42 €                  44 €

Prezzi a persona, a notte. Alta stagione = giugno, luglio, agosto.
Se il soggiorno è a cavallo tra due stagioni, ogni notte viene
conteggiata con la sua tariffa.

Vincoli già impostati: minimo 2 notti, massimo 28, preavviso 24 ore.
Per cambiare tariffe o vincoli, cerca "const TARIFFE" dentro index.html.


BLOCCARE LE DATE OCCUPATE
-------------------------
Apri disponibilita.json e scrivi le date già prenotate così:

  "occupate": ["2026-08-14", "2026-08-15", "2026-08-16"]

Una data per ogni notte occupata, formato AAAA-MM-GG.
Salva, ricarica il file su GitHub, e il calendario si aggiorna.

Per la sincronizzazione automatica con Booking serve il link iCal
del vostro pannello Booking (Calendario > Sincronizza calendari >
Esporta). Mandamelo e configuro l'aggiornamento automatico giornaliero.


LE RICHIESTE DI PRENOTAZIONE
----------------------------
Quando un ospite compila il modulo, si apre WhatsApp verso il numero
di Francesca con il messaggio già scritto: nome, cognome, nazionalità,
città, date, ospiti, età dei bambini, email, orario di arrivo e note.

Per cambiare il numero che riceve le richieste, cerca "const WA_NUM"
dentro index.html.


ANCORA DA FARE
--------------
  - privacy policy e cookie policy
  - denominazione, indirizzo fiscale e P.IVA nel footer
  - foto di copertina ad alta risoluzione (quella attuale è 512 px)
