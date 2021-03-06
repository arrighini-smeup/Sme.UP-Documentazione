# Obiettivo

Generare il file da inviare all'Agenzia delle Entrate, i PDF relativi ai modelli e le stampe di controllo del modello 770.

# Parametri
 \* Anno :  inserire l'anno a cui si riferiscono i dati da stampare e/o trasmettere
 \* Correttiva o Integrativa. E' possibile selezionare : 
 \*\* Normale :  verranno comunicati i record in stato _Da trasmettere_
 \*\* I Integrativa :  verranno comunicati i record in stato _Da integrare_
 \*\* C Correttiva nei termini :  questà modalità è da utilizzare nel caso in cui si sia effettuato u n precedente invio.
 \* Protocollo dichiarazione inviata. Da compilare qualora si stata scelta la dichiarazione correttiva o integrativa. Il campo relativo all'indentificativo dell'invio deve essere compilato nel formato AAMMGG+11 caratteri numerici
 \* Stampa modelli :  impostare 1 se si vuole ottenere la generazione dei pdf dei modelli
 \* Cartella/File da trasmettere :  permette di impostare il nome del file e il percorso di salvataggio. Selezionando il campo comparirà un'ulteriore videata in cui si suggerisce di impostare : 
 \*\* Tipo trasmissione :  5
 \*\* Nome file :  inserire il nome desiderato. Si consiglia di utilizzare l'estensione txt (es. 770_2018_Azienda.txt)
 \*\* Percorso PC :  inserire il percorso della cartella in cui verrà salvato il file da trasmettere all'agenzia delle entrate e i relativi PDF. Nel caso in cui si sia scelto il Tipo trasmissione 5 indicare un percorso all'interno della root.
 \* Modalità :  è possibile selezionare : 
 \*\* Provvisoria
 \*\* Defintiva :  imposterà lo stato dei record a _Trasmesso_ e compilerà la data trasmissione
 \*\* Annulla definitiva :  chiederà la data da annullare e riporterà i record trasmessi in questa data in stato _Da trasmettere_
 \* Dati Responsabile Trasmissione :  compilare nel caso in cui l'invio del file venga effettuato da un intermediario
 \* Dettaglio stampa log :  permette di selezionare se stampare all'interno della stampa di controllo solo i campi compilati o anche i campi vuoti.

# Output
Il programma permette di generare : 
 \* il file da inviare all'Agenzia delle Entrate
 \* i PDF dei modelli ministeriali
 \* una stampa di controllo
