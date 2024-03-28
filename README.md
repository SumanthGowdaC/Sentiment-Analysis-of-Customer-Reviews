# Sentiment Analysis on Reviews

## Description
This Python script performs sentiment analysis on a dataset of reviews using VADER Sentiment and sklearn. It reads a CSV file containing review data, combines the "title" and "text" columns, converts star ratings to sentiments, predicts sentiments for the combined text, computes a confusion matrix, and prints classification report metrics.

## Setup
To run the code, you need the following dependencies:
- pandas
- vaderSentiment
- sklearn
- seaborn
- matplotlib

You can install these dependencies using pip:
```bash
pip install pandas vaderSentiment scikit-learn seaborn matplotlib
