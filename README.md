# Sentiment-analysis

This project focuses on building a Sentiment Analysis model that classifies textual data (IMDB movie reviews) into sentiment categories like Positive and Negative.
The main goal is to apply Machine Learning algorithms to understand the underlying sentiment in text.

## Features

Data preprocessing using HTML tags removal, URL removal, Punctuation removal, stopword removal and vectorization using CountVectorizer and TF-IDF vectorizer.

Model training using supervised learning algorithms like LogisiticRegression, RandomForestClassifier

Evaluation based on metrics such as accuracy, precision, recall, and F1-score.

## Model Development Steps

Data Collection – Imported dataset (IMDb reviews dataset).

Data Cleaning – Removed punctuation, URLs, HTML tags, and stopwords.

Feature Extraction – Converted text into numerical features using TF-IDF or CountVectorizer.

Model Training – Trained multiple models such as:

Logistic Regression

Naïve Bayes

Support Vector Machine (SVM)

Random Forest

Model Evaluation – Compared performance and selected the best model.

Prediction – Tested model on unseen text samples.

## Results

Achieved an accuracy of 86% on the test data.

The Logistic Regression and SVM model showed best performances with high precision and recall scores.

Also checked confusion matrix and ROC-AUC scores for better interpretability.
