# Twitter Sentiment Analysis

## Overview
This project performs sentiment analysis on Twitter data to classify tweets as positive or negative using machine learning techniques. It leverages natural language processing (NLP) to preprocess text and trains three models—Bernoulli Naive Bayes, Linear SVM, and Logistic Regression—to predict sentiment. The project uses a dataset of 1.6 million tweets, achieving a baseline accuracy of up to 62% with the Bernoulli Naive Bayes model.

## Features
- Data Preprocessing: Loads and cleans Twitter data, converting text to lowercase and filtering out neutral sentiments.
- Feature Extraction: Uses TF-IDF vectorization with unigrams and bigrams, limited to 5,000 features.
- Model Training: Implements three classifiers:
- Bernoulli Naive Bayes
- Linear Support Vector Machine (SVM)
- Logistic Regression


## Dataset
The dataset (Sentiment140 dataset) contains 1.6 million tweets with polarity labels (0 for negative, 4 for positive, and 2 for neutral, which is filtered out). The dataset is split into 80% training  and 20% testing.
Dataset Link: https://www.kaggle.com/datasets/kazanova/sentiment140?resource=download

## Results
Model performance on the test set:

- Bernoulli Naive Bayes: 62% accuracy
- Linear SVM: 58% accuracy
- Logistic Regression: 58% accuracy

Detailed classification reports are generated for precision, recall, and F1-score.


