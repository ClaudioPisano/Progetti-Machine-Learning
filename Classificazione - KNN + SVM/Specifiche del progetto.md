**Previsione dell'affidabilità creditizia per il rilascio della carta di credito**

Sei stato assunto dalla Pro National Bank come data scientist, il tuo primo incarico consiste nel realizzare un modello in grado di stimare l'affidabilità creditizia di un clienti, al fine di di aiutare il team dedicato a comprendere se accettare o meno la richiesta per il rilascio della carta di credito.

A tal fine ti vengono consegnati i dati anonimizzati di clienti che hanno già ottenuto la carta di credito e ne pagano regolarmente le rate. 

I dati sono in un file CSV presente a questo indirizzo: [https://proai-datasets.s3.eu-west-3.amazonaws.com/credit\_scoring.csv](https://proai-datasets.s3.eu-west-3.amazonaws.com/credit\_scoring.csv) 

Il file credit\_scoring.csv contiene le informazioni dei correntisti che hanno richiesto l’apertura di una linea di credito.

* **ID**: numero identificativo del cliente  
* **CODE\_GENDER**: sesso del cleinte  
* **FLAG\_OWN\_CAR**: indicatore del possesso di un'automobile  
* **FLAG\_OWN\_REALTY**: indicatore del possesso di una casa  
* **CNT\_CHILDREN**: numero di figli  
* **AMT\_INCOME\_TOTAL**: reddito annuale  
* **NAME\_INCOME\_TYPE**: tipo di reddito  
* **NAME\_EDUCATION\_TYPE**: livello di educazione  
* **NAME\_FAMILY\_STATUS**: Stato civile  
* **NAME\_HOUSING\_TYPE**:   
* **DAYS\_BIRTH**: Numero di giorni trascorsi dalla nascita  
* **DAYS\_EMPLOYED**: Numero di giorni trascorsi dalla data di assunzione, se positivo indica il numero di giorni da quando è disoccupato  
* **FLAG\_MOBIL**: indicatore della presenza di un numero di cellulare  
* **FLAG\_WORK\_PHONE**: indicatore della presenza di un numero di telefono di lavoro  
* **FLAG\_PHONE**: indicatore della presenza di un numero di telefono  
* **FLAG\_EMAIL**: indicatore della presenza di un indirizzo email  
* **OCCUPATION\_TYPE**: tipo di occupazione  
* **CNT\_FAM\_MEMBERS**: numero di familiari  
* **TARGET**: una variabile che vale 1 se il cliente ha una elevata affidabilità creditizia data dal pagamento costante delle rate e 0 altrimenti.

Devi realizzare un modello che preveda il target dato.

PUNTO BONUS

Se ad un cliente viene negata la carta di credito, il team deve essere in grado di fornirgli una motivazione, questo vuol dire che il tuo modello deve fornire delle indicazioni facilmente interpretabili.

