Credit Card Fraud Detection
Project Overview

This project aims to detect fraudulent credit card transactions using machine learning. The models implemented are:

Logistic Regression
Random Forest Classifier

The dataset contains anonymized features of transactions along with the target class indicating fraud (1) or legitimate (0).

Dataset-
Features: Time, Amount, V1–V28
Target: Class (0 = Legitimate, 1 = Fraud)

Project Steps-

Data Preprocessing

Split dataset into features (X) and target (y)
Train-test split (80%-20%)
Standard scaling of features
Model Training-
Logistic Regression
Random Forest Classifier with class_weight='balanced'

Model Evaluation
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)
Comparison of both models’ performance

Results

Logistic Regression: Good baseline performance
Random Forest: Better handling of class imbalance, higher detection rate for fraud
Overall accuracy is high due to the imbalance of classes, but focus is on detecting fraud correctly
