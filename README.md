Questo progetto analizza il dataset Netflix Movies and TV Shows (Kaggle) per comprendere:

la composizione del catalogo (Film vs Serie TV)

i generi più frequenti

i paesi più rappresentati

l’evoluzione del catalogo nel tempo

la distribuzione dei rating

i registi più presenti sulla piattaforma

L’obiettivo è mostrare competenze da Data Analyst attraverso pulizia dei dati, EDA, visualizzazioni e interpretazione dei risultati.

Dataset
Fonte: Kaggle — Netflix Movies and TV Shows  
Il dataset contiene oltre 8.000 titoli con informazioni su:

type (Movie / TV Show)

title

director

cast

country

date_added

release_year

rating

duration

genres

description

year_added (creata durante l’analisi)

🛠️ Tecnologie utilizzate
Python

Pandas

NumPy

Matplotlib

Analisi svolta
1. Esplorazione iniziale
caricamento dataset

analisi struttura

ricerca valori mancanti

statistiche descrittive

2. Pulizia dei dati
gestione dei valori mancanti

conversione date_added in datetime

creazione colonna year_added

3. Analisi esplorativa (EDA)
confronto Movies vs TV Shows

trend dei contenuti aggiunti nel tempo

paesi più rappresentati

analisi dei generi (colonna genres)

distribuzione dei rating

top directors

confronto tra paesi (USA, India, UK)

4. Insight finali
Sintesi dei risultati ottenuti e considerazioni sul catalogo Netflix.


I grafici generati durante l’analisi sono salvati nella cartella:
images/

Seaborn

Jupyter Notebook

Repository cartella:
netflix-analysis/
│
├── data/
│   └── raw/
│       └── NetFlix.csv
│
├── notebooks/
│   └── netflix_analysis.ipynb
│
├── src/
│   └── utils.py
│
|──powerbi/
    └── Dashboard_netflix.pbix
    └── RWADME_powerbi.md
    └── dettaglio_titolo.png
    └── overview.png


Sezione PowerBi:
- KPI principali (Totale titoli, Movie, TV Show)
- Grafico Movie vs TV Show
- Grafico titoli rilasciati per anno
- Grafico titoli aggiunti per anno
- Slicer: Paese, Rating, Anno aggiunta, Genere

└── README.md

