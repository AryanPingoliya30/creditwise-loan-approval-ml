CreditWise Loan Approval Prediction System

This project implements a Machine Learning–based loan approval prediction system for a fictional financial institution, SecureTrust Bank, to automate and improve the accuracy of loan approval decisions.

The system analyzes historical applicant data and predicts whether a loan should be Approved or Rejected, helping reduce manual bias and financial risk.

🚀 Project Overview

Financial institutions receive hundreds of loan applications daily. Manual verification is time-consuming and error-prone.
This project builds an intelligent classification model that:

Learns patterns from past loan data

Predicts loan approval status

Compares multiple ML algorithms

Selects the best-performing model based on evaluation metrics

🧠 Models Implemented

The following machine learning models were trained and evaluated:

Logistic Regression

K-Nearest Neighbors (KNN)

Naive Bayes

After comparison, Naive Bayes was selected as the best model based on Precision and overall classification performance.

📊 Performance (Best Model)

Accuracy: 88%

Precision: 78.46%

Recall: 83.60%

F1-Score: 80.95%

Evaluation was done using:

Confusion Matrix

Precision, Recall, F1-score

Accuracy metrics

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn (for visualization)

Jupyter Notebook

📁 Dataset Features

The dataset includes attributes such as:

Applicant & Co-applicant Income

Credit Score

Employment Status

Loan Amount & Term

Debt-to-Income Ratio

Property Area

Savings & Collateral Value

Loan Purpose

Target: Loan Approved (1) / Rejected (0)

📌 Workflow

Data Cleaning & Preprocessing

Feature Encoding & Scaling

Train-Test Split

Model Training (LR, KNN, Naive Bayes)

Model Evaluation & Comparison

Best Model Selection based on Precision

📈 Future Improvements

Hyperparameter tuning

Ensemble models (Random Forest, XGBoost)

Deployment as a REST API

Integration with a web-based loan portal
