# Un introduzione alla scienza dei dati - Anime Dataset(2023)

Questo è un progetto di introduzione alla scienza dei dati sviluppato per un corso universitario. 
I contenuti trattati, come evidenziato dal nome, sono le basi della scienza dei dati.
Per affrontare tali argomenti si usa come base il dataset MyAnimeList, ricavato da Kaggle, e riferito all'anno 2023.

## Obiettivi del progetto:
Questo notebook esplora un dataset reale per fare pratica con:
- pulizia dei dati e preparazione delle feature
- analisi esplorativa (EDA)
- visualizzazioni
- ragionamento/statistica di base
   
## Domande di ricerca
- Come è cambiata nel tempo la produzione di anime?
- Il punteggio (rating) è correlato alla popolarità?
- Quali generi sono più comuni / più popolari?
- Quali formati (TV, Movie, OVA, ONA, …) sono percepiti meglio?

## Dataset
- **Fonte:** “Dataset Anime 2023 - Kaggle (MyAnimeList dataset)”
- **Autore:** Sajid (pubblicato nel 2023)
- **Campi principali usati nell’analisi:**  
  `Aired`, `Score`, `Genres`, `Type`, `Members`, `anime_id`

## Struttura della repository
- `Anime.ipynb` → notebook principale (analisi)
- `Anime.slides.html` → presentazione/esportazione in formato HTML (apribile dal browser)
- `Dataset/anime-dataset-2023.csv` → dataset (percorso atteso dal notebook)

## Come eseguire il progetto
### 1) Setup (consigliato)
Crea un ambiente virtuale e installa i pacchetti necessari:

```bash
pip install -U pip
pip install pandas numpy matplotlib seaborn scipy jupyter
