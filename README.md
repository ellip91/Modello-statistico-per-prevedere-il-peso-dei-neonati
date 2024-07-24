**Un modello statistico per prevedere il peso dei neonati**

Il progetto ha lo scopo di creare un modello per la previsione del peso dei neonati basandosi sullo studio di variabili legate alla madre e al nascituro stesso.

I dati presenti nel dataset includono 2500 osservazioni raccolte da 3 differenti ospedali con 10 variabili per ciascuna osservazione.  

Le variabili presenti nel dataset sono le seguenti:  

-età della madre  
-numero di gravidanze sostenute  
-Madre fumatrice (0=NO, SI=1)  
-N° di settimane di gestazione  
-peso in grammi del neonato  
-Lunghezza in mm del neonato  
-Diametro in mm del cranio del neonato  
-Tipo di parto: Naturale o Cesareo  
-Ospedale: 1, 2, 3  
-Sesso del neonato: M o F  

Per prevedere il peso del nascituro, è stata studiata l'influenza di ciascuna variabile sulla variabile di risposta **Peso** al fine di creare un modello di regressione lineare multipla. 
Sono stati eseguiti vari test, come il Test di Correlazione, il Test T di Student e il Test del Chi Quadrato, per verificare varie ipotesi.
Inoltre,  per la visualizzazione dei dati è stato utilizzato ggplot2.
