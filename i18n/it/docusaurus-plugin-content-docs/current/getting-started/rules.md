---
sidebar_position: 1
title: Regole di compilazione dei bug
---

# Regole di compilazione dei bug

Fai riferimento alle regole riportate in questo articolo ogni qual volta tu debba riempire i vari campi previsti nel form di segnalazione di un bug; in questo modo, i tuoi bug verranno approvati più velocemente e con meno richieste integrative, inoltre riceverai più punti esperienza.

Ogni bug deve essere sempre scritto in modo da poter essere compreso senza visualizzarne gli allegati.

### Titolo del bug

Il titolo deve presentare la sezione o il processo in cui il problema si verifica inscritto tra parentesi quadre (non il nome o il numero dello use case), seguito da un riassunto breve e comprensibile del problema, in modo che possa essere compreso e distinto chiaramente.

:::danger Titolo scorretto

[USE CASE 1] – L’accesso non funziona

[Home] – Errore

:::

:::tip Titolo corretto

[Login] – Impossibile effettuare l’accesso usando credenziali

:::

### Descrizione step-by-step
La descrizione del bug deve presentare un elenco puntato di azioni da effettuare per poter replicare il percorso che ha portato al problema. Ogni singolo passaggio deve essere riportato in un passo (preceduto dal suo numero) in modo chiaro, identificando univocamente il comportamento dell’utente sul prodotto (ad es. tap, click, indietro sullo smartphone o sul browser) e le scelte effettuate o i tasti cliccati (i nomi delle sezioni o dei bottoni devono essere scritti tra virgolette). Inoltre, eventuali precondizioni vanno esplicitate sempre nei primi punti.
Attenzione: l’ultimo step non deve essere la descrizione del Bug. Questa va descritta nel campo “Actual result”.

:::danger Descrizione scorretta
1. Aprire l’App;
2. Click su Login;
- Caricamento.
:::

:::tip Descrizione corretta
1. Aprire l’app appena installata e atterrare sulla pagina di login;
2. Compilare i campi con una credenziale corretta;
3. Cliccare sul bottone “Effettua l’accesso”.
:::

### Risultato previsto
Il risultato atteso deve descrivere esclusivamente quello che sarebbe dovuto essere il comportamento del prodotto digitale, che invece non si è realizzato, riferendosi sempre al contesto in cui il bug si è verificato.

:::danger Risultato atteso scorretto
Login.
:::

:::tip Risultato atteso corretto
L’utente dovrebbe visualizzare l’area riservata agli utenti che hanno effettuato il login.
:::


### Risultato ottenuto
Il risultato effettivo descrive in modo completo il comportamento del prodotto in riferimento al bug che si è verificato all’interno del suo contesto di riproducibilità. Eventuali comportamenti simili adottando procedure leggermente diverse vanno riportate in questo campo, così come vanno indicati anche eventuali dettagli sulla riproducibilità del bug.

:::danger Risultato effettivo scorretto
Il login non avviene.
:::

:::tip Risultato effettivo corretto
Visualizzazione infinita dell’icona di caricamento, senza possibilità di accesso. Anche provando con “ricorda credenziali” il problema persiste ad ogni tentativo.
:::

### Altri commenti

I commenti aggiuntivi non sono obbligatori e sono riservati ad eventuali osservazioni generali che non dettagliano gli step ma aiutano a prendere contesto del problema.

:::tip Commenti aggiuntivi corretti
Il problema si verifica indipendentemente dal browser usato.
:::

### Caricamento degli allegati
Ogni bug deve presentare sempre degli allegati per facilitare la comprensione del problema,  1 screenshot e 1 video in cui vengano mostrate le azioni effettuate e il risultato ottenuto. È sempre obbligatorio caricare almeno 1 screenshot e 1 video (*). 

Il video deve essere sufficientemente lungo da mostrare i passi eseguiti e il problema che si verifica; Nella registrazione del video è vietato registrare l’audio raccontando ciò che si sta facendo;

:::info video (*)
Solamente nella casistica TYPO si può non allegare il video, ma 2 screenshot.
:::
