# Flip.kz Market Analysis

A data analysis project scraping and analyzing book market data from [flip.kz](https://flip.kz), covering pricing, discounts, ratings, publisher trends, and sentiment analysis.

---

## Dependencies

Install required libraries:

```bash
pip install requests beautifulsoup4 pandas numpy seaborn matplotlib plotly scikit-learn nltk textblob wordcloud
```

Download NLTK data (run once):

```python
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
```

Standard library modules used (no installation needed): `re`, `time`, `warnings`

---

## How to Run

1. Install dependencies (see above)
2. Open the notebook in Jupyter and run all cells sequentially

---

## Data Source

Data scraped from [flip.kz](https://flip.kz) — a Kazakhstani online bookstore.
