# Website Review Sentiment Checker

This project performs basic sentiment analysis on website review text using **VADER SentimentIntensityAnalyzer** from NLTK.

> Designed as a lightweight NLP demo for detecting review tone using compound sentiment scoring.

---

##  How It Works

- Prompts the user for input text (e.g., a website review)
- Uses NLTK’s `SentimentIntensityAnalyzer` to generate sentiment scores
- Classifies the input as:
  - `Positive` if compound score > 0
  - `Negative` if < 0
  - `Neutral` if = 0



