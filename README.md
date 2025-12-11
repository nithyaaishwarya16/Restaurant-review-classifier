# Restaurant-review-classifier
# Restaurant-Review-Classifier
Project Overview
The Restaurant Review Classifier is an AI-based sentiment analysis system that categorizes restaurant feedback into Positive or Negative sentiments. Using Natural Language Processing (NLP), the model analyzes customer opinions and highlights the service aspects they frequently mention, such as food quality, staff behavior, hygiene, pricing, and ambience. This project aids restaurant businesses in understanding customer satisfaction and improving decision-making.

Technical Workflow
Dataset Acquisition – Restaurant feedback dataset containing labeled sentiment values.
Text Preprocessing – Cleaning, tokenizing, removing stopwords, and stemming using NLTK.
Feature Extraction – Transformation into numerical data using TF-IDF.
Model Training – Trained multiple ML models and selected the best-performing algorithm.
Deployment – Integrated the model into a Flask web application for real-time sentiment prediction.

Technologies Used
Programming Language: Python
Libraries: NLTK, Scikit-Learn, NumPy, Pandas
ML Algorithm: Bernoulli Naive Bayes (Accuracy: 77%)
Web Framework: Flask
Frontend: HTML, CSS
Model Saving: Pickle

Key Features
✔ Real-time sentiment prediction
✔ Clean and user-friendly web interface
✔ Fast and lightweight ML model
✔ Works locally without internet
✔ Extracts meaningful aspects from feedback


Model Performance
Model	Accuracy
Bernoulli Naive Bayes	77%
Logistic Regression	75%
SVM	73%
Random Forest	73%
KNN	68.5%


Developed by Pranusha Katta
B.Tech, SRM University – AP
