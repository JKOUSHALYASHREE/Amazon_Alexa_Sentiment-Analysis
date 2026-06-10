Amazon Alexa Reviews Sentiment Analysis
Overview

This project focuses on analyzing customer reviews of Amazon Alexa products using Natural Language Processing (NLP) and Machine Learning. The objective is to automatically determine whether a customer review expresses positive or negative sentiment, helping businesses understand customer satisfaction and product perception at scale.

By combining text preprocessing, feature extraction, exploratory data analysis, and machine learning models, the project transforms raw customer feedback into actionable insights.

Problem Statement

Customer reviews contain valuable information about user experiences, product quality, and customer satisfaction. However, manually analyzing thousands of reviews is time-consuming and inefficient.

This project addresses the problem by building an automated sentiment classification system capable of identifying positive and negative reviews from textual feedback.

Dataset

The dataset consists of Amazon Alexa product reviews containing:

Customer ratings
Review text
Feedback labels
Additional review-related attributes
Project Workflow
1. Data Exploration and Analysis (EDA)
Dataset inspection
Missing value analysis
Class distribution analysis
Review statistics and visualizations
2. Data Preprocessing
Text cleaning
Removal of special characters and punctuation
Lowercase conversion
Stopword handling
Feature preparation
3. Feature Engineering
Count Vectorization
Text-to-numeric transformation
Feature scaling where applicable
4. Model Development

Multiple machine learning models were trained and evaluated:

Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier
5. Model Evaluation

Performance was evaluated using:

Accuracy Score
Confusion Matrix
Classification Metrics
6. Deployment

A Flask-based web application was developed to allow users to enter reviews and obtain sentiment predictions in real time.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
XGBoost
Flask
Pickle
Project Structure
├── Data Exploration & Modelling.ipynb
├── api.py
├── countVectorizer.pkl
├── scaler.pkl
├── model_dt.pkl
├── model_rf.pkl
├── model_xgb.pkl
├── requirements.txt
└── README.md
Key Learnings
Natural Language Processing fundamentals
Text preprocessing techniques
Feature extraction using CountVectorizer
Machine Learning model comparison
Model serialization using Pickle
Flask deployment for ML applications
Future Improvements
Transformer-based sentiment analysis using BERT
Review summarization using LLMs
Interactive analytics dashboard
Product recommendation insights
Retrieval-Augmented Generation (RAG) for customer feedback analysis
