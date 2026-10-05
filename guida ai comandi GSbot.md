#gsbot

# Comandi GSbot

## Test

`/test`  
Verifica che GSbot sia operativo e connesso correttamente al server. Risponde in privato con un messaggio diagnostico semplice.

---

## Compleanni

`/birthday set <giorno> <mese> [anno]`  
Imposta o aggiorna il proprio compleanno.

`/birthday remove`  
Rimuove il proprio compleanno dal sistema.

`/birthday show [utente]`  
Mostra il compleanno configurato per sé o, se specificato, per un altro utente.

`/birthday test`  
Mostra in privato un'anteprima del messaggio di compleanno usando lo stesso renderer e la stessa randomizzazione del reminder reale.

Il reminder vero viene inviato automaticamente nel giorno del compleanno.

---

## Tag temporanei

`/tag create`  
Apre una modal per creare un nuovo tag temporaneo. Permette di configurare:

*   nome del tag;
*   testo del bottone;
*   scadenza opzionale.

Crea subito il relativo ruolo Discord, senza pubblicare alcun invito.

`/tag invite <tag>`  
Pubblica nel canale corrente il bottone configurato per quel tag.

Gli utenti possono cliccarlo per:

*   ricevere il tag;
*   cliccarlo di nuovo per rimuoverselo.

`/tag info <tag>`  
Mostra in privato le informazioni del tag:

*   numero di membri;
*   scadenza;
*   numero di inviti attivi;
*   creatore;
*   data di creazione.

`/tag list`  
Mostra in privato la lista dei tag temporanei attualmente attivi, con numero di membri e scadenza.

`/tag delete <tag>`  
Elimina un tag temporaneo dopo una conferma esplicita.

L'operazione:

*   elimina il ruolo Discord;
*   disabilita tutti i bottoni associati;
*   conserva lo storico nel database.

I tag con scadenza vengono eliminati automaticamente allo stesso modo.
