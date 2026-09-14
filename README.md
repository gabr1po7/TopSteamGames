# Quanto conta il prezzo su Steam?

Progetto per il corso di Data Science e Laboratorio — Università di Udine.
Analisi dei 1000 giochi più venduti su Steam a marzo 2026, a partire dal dataset
[Top 1000 Steam Games](https://www.kaggle.com/datasets/waddahali/top-1000-steam-games-20242026) di Kaggle.

## File

- **`data/steam_games_2026.csv`**: dati grezzi, mai modificati.
- **`preprocessing.ipynb`**: ispeziona il dataset, documenta i problemi trovati e produce il file pulito.
- **`preprocessed/steam_pulito.parquet`**: output del preprocessing, è ciò che legge l'analisi.
- **`analysis.ipynb`**: risponde alle tre domande del progetto.
- **`presentazione.ipynb`**: sorgente delle slide.
- **`presentazione.slides.html`**: slide esportate, da aprire nel browser.

Eseguire `preprocessing.ipynb` prima di `analysis.ipynb`.
