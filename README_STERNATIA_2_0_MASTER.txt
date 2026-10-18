WEBGIS STERNATIA 2.0 — README DELLA VERSIONE MASTER
Aggiornato: 18/10/2026

1. DESCRIZIONE
WebGIS indipendente di divulgazione cartografica dedicato al territorio di Sternatia e all'incendio del 2017. Non è un servizio ufficiale del Comune e non sostituisce atti o certificazioni amministrative.

2. STRUTTURA DA CONSERVARE
index.html (pagina principale)
css/ — stili
js/ — librerie e script
 data/ — dati cartografici
legend/ — simboli e legende
webfonts/ — caratteri e icone
Conservare tutte queste cartelle insieme al file index.html. Non sostituire soltanto index.html quando si passa a una nuova versione.

3. APERTURA LOCALE
Aprire index.html con Firefox, anche tramite doppio clic. L'esportazione qgis2web include le librerie necessarie e carica i dati GeoJSON locali. Le mappe di sfondo online e i collegamenti esterni richiedono Internet.

4. FUNZIONI
- Pannello per attivare/disattivare i layer e regolarne la trasparenza.
- Immagini Copernicus relative al periodo dell'incendio 2017.
- Particelle interessate e perimetro dell'incendio.
- Curve di livello ogni 5 metri.
- Icona informazioni (i) in basso a sinistra.
- Navigazione: premere «Indicazioni», scegliere un punto sulla mappa e nel popup premere «Apri percorso in Google Maps». Google Maps gestisce la partenza in base alle impostazioni e autorizzazioni dell'utente.
- Scheda informativa dei vincoli associata al layer inc_Sternatia_2017.

5. VINCOLI: ATTENZIONE ALLE DATE
La scheda richiama l'art. 10 della legge 353/2000, la legislazione regionale pugliese e l'Ordinanza del Comune di Sternatia n. 33 del 30/06/2021. La data di pubblicazione dell'ordinanza è stata confermata dall'utente, ma ciò NON dimostra che ogni divieto decorra da quella data.
Le durate o le eventuali date calcolate visualizzate nel WebGIS sono indicative: non attestano l'esistenza, l'effettiva decorrenza, la cessazione o l'applicabilità del vincolo a una specifica particella. Verificare il testo integrale dell'ordinanza, la normativa vigente, la categoria del soprassuolo e gli atti ufficiali prima di pubblicare indicazioni come «ATTIVO» o «SCADUTO».
Riferimenti istituzionali:
Legge 353/2000: https://www.parlamento.it/parlam/leggi/00353l.htm
Normativa Regione Puglia: https://bussolanormativa.consiglio.puglia.it/public/Leges/LeggeNavscroll.aspx?id=12862

6. PUBBLICAZIONE — NON ANCORA PRONTA
Questa MASTER è una versione di lavoro/test, NON ancora approvata per la pubblicazione pubblica.
Prima di pubblicare su GitHub Pages o su altro sito:
- sostituire lo sfondo Google Satellite utilizzato nei test con una fonte il cui uso nel WebGIS sia autorizzato;
- verificare licenze, attribuzioni e possibilità di redistribuzione di ortofoto, dati catastali, layer e immagini satellitari;
- verificare contenuti legali, dati sensibili e informazioni pubblicabili;
- provare il WebGIS su desktop e smartphone.
Il fatto che un testo normativo sia collegabile tramite URL non autorizza automaticamente il riutilizzo degli altri dati cartografici.

7. BACKUP E VERSIONI
Conservare intatta Sternatia_2_0_MASTER e una copia di sicurezza. Per modifiche future lavorare su una copia separata. Conservare anche qgis2web_BACKUP e il progetto originale QGIS nella cartella 01_Originale_QGIS.

Nota: questo README riunisce i quattro TXT delle prove precedenti. Le istruzioni della configurazione iniziale descrivevano uno stato di test e non garantiscono quali layer siano oggi accesi per impostazione predefinita.
