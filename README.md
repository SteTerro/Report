# Analisi del dataset Mussels

## Introduzione
La seguente relazione è una analisi del dataset `Mussels`. Il dataset è per primo apparso nello studio *Distribution of freshwater mussels: coastalrivers as biogeographic islands* del 1974 di J.J. Sepkoski, Jr. e Michael A. Rex. 
Lo scopo dell'Analisi è individuare quali fattori influenzano la distribuzione di specie di cozze di acqua dolce in 44 fiumi della costa orientale degli Stati Uniti. 
Sono stati analizzati 44 fiumi compresi tra la foce del fiumi St. Lawrence e lo stato dell'Alabama. 
Mediante l'analisi di 79 specie di cozze, la ricerca ha esaminato fattori come l'area di drenaggio del fiume, la prossimità a sistemi fluviali principali (quali Alabama-Coosa, Apalachicola, Savannah e St. Lawrence) e alcuni parametri di qualità dell'acqua.

Le variabili analizzate sono:
- `Area`: area di drenaggio del fiume;
- `Stepping Stones to AP`: distanza dal fiume Apalachicola;
- `Stepping Stones to AC`: distanza dal fiume Alabama-Coosa;
- `Stepping Stones to SV`: distanza dal fiume Savannah;
- `Stepping Stones to SL`: distanza dal fiume St. Lawrence;
- `Solid Residue`: concentrazione di residuo fisso nelle acque dei fiumi;
- `Nitrate`: concentrazione di nitrati nelle acque dei fiumi;
- `Hydronium`: concentrazione di ioni idrogeno nelle acque dei fiumi;

Sono stati stimati due modelli: un modello lineare multiplo e un modello di Poisson.
Il modello di Poisson si è dimostrato il più appropriato, il modello contiene l'area di drenaggio del fiume, la prossimità al fiume Apalachicola, la concentrazione di residui solidi e i livelli di ioni idronio.
Questi fattori combinati nel modello riescono a spiegare il 78% della variabilità della distribuzione di specie di cozze nei fiumi dell'area analizzata.

## Contenuto della Cartella
La repository contiene:
- `relazione.pdf`: il file pdf della relazione;
- `relazione.tex`: il file con il codice latex;
- `report.Rmd`: il file in formato R markdown contenete le varie analisi contenute nella relazione;
- `immagini`: cartella contenente i vari grafici riportati nel report;
