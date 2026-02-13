# Opinion Mining & Sentiment Analysis (LinkedIn Reviews)

This project performs opinion mining (sentiment analysis) on LinkedIn review text using:
- Text cleaning + tokenization (NLTK)
- WordCloud visualization
- VADER Sentiment analysis (vaderSentiment)
- Deep Learning demo models (LSTM / CNN / Bidirectional LSTM)

## Files in this repository
- `opinion-mining.ipynb` — main notebook
- `ready.txt` — text used for WordCloud
- `vader_table1.csv` — LinkedIn review dataset (Serial number, text)
- `requirements.txt` — dependencies

## How to run (Local)
1. Install dependencies:
   ```bash
   pip install -r requirements.txt


Download NLTK data (first time only):

python -m nltk.downloader stopwords punkt


Start Jupyter:

jupyter notebook


Open and run:

opinion-mining.ipynb
