 - Ripristinare dal supporto la SMEUP_DEV.
 - Chiamare il programma B£UT03 (UP UT3) per estrarre le tabelle dalla SMEUP_DEV e aggiornare la cartella di help (che deve esistere, altrimenti viene segnalato un errore).
 - Eseguire una fasatura delle tabelle attraverso il comando UP FTB. Prestare attenzione alle tabelle standard personalizzate e alle deviazioni eventualmente impostate.
 - Controllare le informazioni sui rilasci effettuati e l'help tecnico, tramite il comando UP PTF. Si ricorda di riempire prima la tabella B§V con le librerie giuste.
 - Sempre tramite UP PTF, allineare i campi numerici delle tabelle e i vari archivi e logici nuovi o modificati.
 - Sostituire nella lista librerie la nuova SMEUP_DEV.
 - Concedere / controllare le autorizzazioni sugli oggetti della nuova SMEUP_DEV.
 - Riallineare i programmi standard personalizzati introducendo le modifiche effettuate sui nuovi programmi, sempre che ce ne sia ancora bisogno (se una funzionalità è stata inserita nello standard).
 - Controllare (per eventuali modifiche alle /COPY, tabelle, archivi) i programmi personalizzati del cliente e ricompilarli.
 - Ricompilare le eventuali interfacce utilizzate presenti nella SMEUP_DEV, in quanto non esiste l'oggetto (i sorgenti sono presenti nei file SRC_xx, dove xx è l'ambiente).
 - Fasare le lingue, se necessario.
