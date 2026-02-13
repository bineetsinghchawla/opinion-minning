# Opinion Mining & Sentiment Analysis (LinkedIn Reviews)

This repository contains an opinion mining (sentiment analysis) project on LinkedIn review text using NLP techniques and VADER sentiment scoring, along with deep learning model experiments.

## What this project does
- Cleans and preprocesses review text
- Generates WordCloud from text
- Computes sentiment using VADER (positive / negative / neutral + compound score)
- Experiments with deep learning models (LSTM / CNN / Bidirectional LSTM)

## Files
- `opinion-mining.ipynb` — main notebook (run this)
- `vader_table1.csv` — dataset used in the notebook
- `ready.txt` — text file used for WordCloud
- `requirements.txt` — required Python packages

## How to run (Local)
1) Install dependencies
```bash
pip install -r requirements.txt
````

2. Download NLTK data (first time only)

```bash
python -m nltk.downloader stopwords punkt
```

3. Start Jupyter

```bash
jupyter notebook
```

4. Open and run

* `opinion-mining.ipynb`

## Notes

* Keep `vader_table1.csv` and `ready.txt` in the same folder as the notebook, otherwise file paths will break.

```
::contentReference[oaicite:0]{index=0}
```
