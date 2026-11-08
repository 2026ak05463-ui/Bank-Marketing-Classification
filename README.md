Bank Marketing Classification

Project Overview

This project applies five machine learning classification algorithms to the Bank Marketing dataset to predict whether a customer will subscribe to a term deposit.

The project includes data preprocessing, model training, evaluation using multiple performance metrics, and a Streamlit web application for model evaluation and prediction.

Dataset

Dataset: Bank Marketing Dataset

Source: UCI Machine Learning Repository

Instances: 4,521

Features: 16 input features

Target variable: y (yes/no)

Machine Learning Models

The following five classification models are implemented:

Logistic Regression

Decision Tree

K-Nearest Neighbors (KNN)

Gaussian Naive Bayes

Support Vector Machine (SVM)

Evaluation Metrics

The models are evaluated using:

Accuracy

Area Under the ROC Curve (AUC)

Precision

Recall

F1 Score

Matthews Correlation Coefficient (MCC)

Streamlit Application

The application allows users to:

Select a trained classification model

Upload a test CSV file

View evaluation metrics

View the confusion matrix and classification report

Generate predictions

Project Structure

Bank-Marketing-Classification/
├── app.py
├── ML Ass 2.ipynb
├── bank.csv
├── test_data.csv
├── models/
│   ├── logistic_regression.pkl
│   ├── decision_tree.pkl
│   ├── knn.pkl
│   ├── gaussian_naive_bayes.pkl
│   └── svm.pkl
└── README.md

How to Run the Application

Install the required packages:

pip install streamlit pandas scikit-learn joblib

Run the Streamlit application:

streamlit run app.py

The application will open in your browser.

Repository

Bank-Marketing-Classification on GitHub
