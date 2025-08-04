# Toxic_Tweet_Detector
Machine Learning project for Toxic Tweet Classification using NLP. Includes data preprocessing, feature extraction, model training, and evaluation for detecting toxic and non-toxic tweets.

This project classifies tweets as toxic or non-toxic using Natural Language Processing (NLP) and Machine Learning.
It covers text preprocessing, TF-IDF feature extraction, model training, and evaluation.

Dataset
Tweets labeled as toxic (1) or non-toxic (0)

Example:

tweet	label
"I hate you so much!"	--1
"Have a great day everyone!"--0

Workflow
  Data cleaning (remove URLs, hashtags, mentions, stopwords)

  TF-IDF vectorization

  Model training (Logistic Regression, Naive Bayes)

  Evaluation (Accuracy, F1 Score)

How to Run
  Clone the repo

  Install dependencies:
  
    pip install -r requirements.txt
  
  Open and run Toxic_Tweet_Classification.ipynb

Results
Best Model: Logistic Regression

Accuracy: ~92%

