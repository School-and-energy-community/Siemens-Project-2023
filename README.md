# School and Energy Community
## Campionato Nazionale Siemens 2023
### Finalità
Il presente progetto ha come finalità il monitoraggio energetico di edifici al fine di ottenere:
- in fase **preliminare** le informazioni utili per il dimensionamento di impianti di produzione da energia rinnovabile a servizio comunità energetiche;
- a **regime** le informazioni dettagliate circa il consumo degli impianti costituenti la comunità energetica.

Il monitoraggio energetico si riferisce sia all'energia **elettrica** sia all'energia **termica** o ad altra forma di energia prodotta o immagazzinazzinata, come ad esempio quella **chimica** o quella ottenibile dallo stoccaggio di gas come l'aria compressa.

Il sistema di monitoraggio si basa su componenti a bassissimo costo con alto livello di affidabilità, alimentati a batteria in modo che possano essere inseriti in qualsiasi impianto in modo non intrusivo e sicuro, ovvero senza la necessità di dover intervenire e/o modificare l'impianto oggetto di monitoraggio.
Tali componenti sono in grado di trasmettere le informazioni senza intermediari web direttamente su Google Sheet per essere elaborati da opportuna interfaccia software.

### Architettura e funzioni del sistema di monitoraggio
La figura seguente mostra il sistema a stella del sistema di monitoraggio low cost
 
<img src="image/diag1.jpg" width="550" height="350">

Inizialmente i dati raccolti dal sistema di monitoraggio consentono di definire il **comportamento termodinamico degli edifici** nonchè **l'andamento temporale dei consumi energetici**. Successivamente quando la comunità energetica è attiva, il sistema di monitoraggio fornisce informazioni in tempo reale dei **periodi in cui i consumi risultano economicamente piu' favorevoli** a seguito della disponibilità della risorsa rinnovabile. Le stesse informazioni sono inoltre utilizzate per le attività di **manutenzione ordinaria e straordinaria degli impianti**. In altre parole il sistema di monitoraggio facilita la gestione e l'utilizzo di un impianto complesso a servizio di una comunità energetica rendendolo **accessibile** ovvero semplicemente **fruibile** anche ad utenti non esperti.



