# School and Energy Community
## Campionato Nazionale Siemens 2023
<img src="image/photo.gif" width="150" height="130"> <img src="image/eolico.gif" width="150" height="130">

###Premessa###
riflessioni degli studenti sul tema ambientale - contributo docente di lettere Prof.ssa Lencioni  
### Finalità
Il presente progetto ha come finalità il monitoraggio energetico di edifici al fine di ottenere:
- in fase **preliminare** le informazioni utili per il dimensionamento di impianti di produzione da energia rinnovabile a servizio comunità energetiche;
- a **regime** le informazioni dettagliate circa il consumo degli impianti costituenti la comunità energetica.

Il monitoraggio energetico si riferisce sia all'energia **elettrica** sia all'energia **termica** o ad altra forma di energia prodotta o immagazzinata.

Il sistema di monitoraggio utilizza componenti a bassissimo costo di dimensioni ridotte e con alto livello di affidabilità. Alimentati a batteria sono adatti per essere inseriti in qualsiasi impianto in modo non intrusivo e sicuro, ovvero senza la necessità di dover intervenire e/o modificare i circuiti oggetto di monitoraggio.
Tali componenti sono in grado di trasmettere le informazioni senza intermediari web direttamente su Google Sheets per essere elaborati da opportuna interfaccia software.

### Peculiarità del progetto
Il presente lavoro si rivolge a tutti, in particolare ai non esperti, utilizzando tecnologie robuste ed affidabili a bassisimo costo e open source come Google Scripts. La parola d'ordine è **semplificare il piu' possibile** rendendo accessibile a chiunque concetti e pratiche che spesso sono per addetti ai lavori.  In altre parole chiunque abbia uno smartphone e ovunque si trovi, purchè vi sia un segnale WiFi disponibile, è in grado di *addestrare* il sistema di monitoraggio e di leggere i propri consumi energetici. Di seguito, oltre al video istituzionale del Campionato Siemens, saranno proposti dei video-tutorial esplicativi sull'addestramento e sull'utilizzo del sistema di monitoraggio.

### Semplificare la parola d'ordine ma ... senza banalizzare !
Voler caratterizzare i consumi di piu' utilizzatori attraverso un'unica misura a monte dell'impianto è un argomento studiato da tempo. Si possono trovare online diversi [studi accademici](https://scholar.google.it/scholar?q=non+intrusive+load+monitoring+academic&hl=it&as_sdt=0&as_vis=1&oi=scholart) che trattano l'argomento di questa tecnica che prende il nome di [NILM](https://en.wikipedia.org/wiki/Nonintrusive_load_monitoring) che significa *Non intrusive load monitoring*. Nella sostanza, alla base del metodo, c'è lo studio, la ricerca di come poter **disaggregare** il dato numerico della misura. Infatti ad ogni carico elettrico  collegato corrisponde a monte un aumento di corrente assorbita. La misura quindi è un dato **aggregato** che corrisponde alla somma di tutte le correnti 

<img src="image/prese.gif" width="150" height="130">

Ogni sforzo quindi è nel tentativo di riconoscere da una somma 


### Architettura e funzioni del sistema di monitoraggio
La figura seguente mostra il sistema a stella del sistema di monitoraggio low cost
 
<img src="image/diag1.jpg" width="550" height="350">

Inizialmente i dati raccolti dal sistema di monitoraggio consentono di definire il **comportamento termodinamico degli edifici** nonchè **l'andamento temporale dei consumi energetici**. Successivamente quando la comunità energetica è attiva, il sistema di monitoraggio fornisce informazioni in tempo reale dei **periodi in cui i consumi risultano economicamente piu' favorevoli** a seguito della disponibilità della risorsa rinnovabile. Le stesse informazioni sono inoltre utilizzate per le attività di **manutenzione ordinaria e straordinaria degli impianti**. In altre parole il sistema di monitoraggio facilita la gestione e l'utilizzo di un impianto complesso a servizio di una comunità energetica rendendolo **accessibile** ovvero semplicemente **fruibile** anche ad utenti non esperti.

### Video progetto ###
Video istituzionale di 4 minuti -- under construction

### Attività di laboratorio ###
#### Calibrazione TA ####
Il TA per la misura della corrente è stato testato con carichi crescenti utlizzando un amperometro da laboratorio

<img src="image/TA.png" width="200" height="140">

Il segnale analogico del TA è stato digitalizzato per l'acquisizione da parte dell'ESP32.
I valori digitali della tensione sono stati interpolati mediante regressione lineare.

<img src="image/reglin1.png" width="440" height="280">

#### Calibrazione PT100 ####
segue esperienza laboratorio

<img src="image/uc.png" width="220" height="140">


