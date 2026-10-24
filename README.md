# Sentiment Analysis (NLP · VADER)

Sentiment analysis of Amazon review text with **NLTK's VADER** lexicon — scoring reviews and summarizing how sentiment distributes across the dataset.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green)

## Overview

## Origin

This project was originally developed inside the `Data-Science` notebook collection and now lives in its own repository for easier discovery and use.

The notebook loads an Amazon reviews dataset (the PyCaret sample hosted on GitHub), applies VADER's `SentimentIntensityAnalyzer` to score each review's sentiment, and visualizes the results with Matplotlib — a compact introduction to lexicon-based NLP sentiment analysis.

## What's Inside

- `sentiment_analysis.ipynb` — load reviews → VADER polarity scores → aggregation & plots

## Getting Started

```bash
git clone https://github.com/datascientist970/sentiment-analysis-nlp.git
cd sentiment-analysis-nlp
pip install -r requirements.txt
jupyter notebook sentiment_analysis.ipynb
```

The notebook downloads the dataset from a public GitHub URL, so an internet connection is enough to run it end-to-end.

## Tech Stack

Python · NLTK (VADER) · Pandas · scikit-learn · Matplotlib

## Author

**Muhammad Dawood** — AI & Data Science Engineer
GitHub: https://github.com/datascientist970 · LinkedIn: https://www.linkedin.com/in/dawood406/
Mardan, Khyber Pakhtunkhwa, Pakistan
