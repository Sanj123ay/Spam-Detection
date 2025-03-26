# Spam-Detection

Overview
This project implements a machine learning model to classify SMS messages as either "spam" or "ham" (legitimate). The model uses natural language processing techniques and various classification algorithms to accurately identify unwanted messages.

Features
Text preprocessing (lowercasing, punctuation removal, stopword removal, stemming)

TF-IDF vectorization for feature extraction

Multiple classifier options:

Naive Bayes

Logistic Regression

Random Forest

Support Vector Machine

Performance evaluation metrics (accuracy, precision, recall, F1-score)

Requirements
Python 3.x

pandas

scikit-learn

nltk

Usage
Clone the repository

Install dependencies: pip install -r requirements.txt

Run the script: python spam_detection.py

Results
The model achieves high accuracy (>95%) in distinguishing between spam and legitimate messages, with detailed performance metrics for each classifier.
