Funzionalità di valutazione della chiarezza informativa
============================================================

Il sito di un museo deve permettere agli utenti di valutare la chiarezza informative delle pagine, come da indicazione dell'**eGovernment Benchmark**. Questa funzionalità deve essere presente su ogni pagina del sito, prima del footer.

Il componente è stato progettato usando una scala che vuole misurare la chiarezza dei contenuti e, in base alla valutazione ricevuta dall'utente, offre domande chiuse e aperte in maniera standardizzata, in modo tale da poter raccogliere feedback utile all'ente per migliorare le pagine del sito. Il componente è disponibile nella Libreria UI del modello Musei su Figma.

  
La funzionalità si articola nei seguenti passaggi:

1. viene posta la domanda "Quanto sono chiare le informazioni su questa pagina?", a cui l'utente risponde con una scala Likert 1-5 sotto forma di stelline;

2. in base alla risposta dell'utente, il secondo passaggio presenta 2 varianti:

  Se il punteggio dell'utente è inferiore a 4 (1-3), viene posta la domanda a risposta multipla "Dove hai incontrato le maggiori difficoltà?". Le possibili risposte sono:

  - A volte le indicazioni non erano chiare
  - A volte le indicazioni non erano complete
  - A volte non capivo se stavo procedendo correttamente 
  - Ho avuto problemi tecnici
  - Altro

  Se il punteggio è pari o superiore a 4 (4-5) il testo della domanda sarà: "Quali sono stati gli aspetti che hai preferito?". Le possibili risposte:

  - Le indicazioni erano chiare
  - Le indicazioni erano complete
  - Capivo sempre che stavo procedendo correttamente
  - Non ho avuto problemi tecnici
  - Altro


3. viene presentato un campo di testo libero per dare la possibilità all'utente di inserire un breve commento, introdotto dalla domanda "Vuoi aggiungere altri dettagli?"

4. All'invio del feedback, il messaggio "Grazie, il tuo parere ci aiuterà a migliorare il sito!" conferma all'utente la riuscita dell'invio.
