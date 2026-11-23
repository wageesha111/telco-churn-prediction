# telco-churn-prediction
# Telco Customer Churn Prediction – CM2604 Machine Learning Coursework

Binary classification to predict whether a telecom customer will churn, using the
Telco Customer Churn dataset (IBM / Kaggle).

## Models
- K-Nearest Neighbours (KNN)
- Logistic Regression
- Random Forest

Each model is run with default settings and with hyperparameters tuned by GridSearchCV (5-fold CV, F1 score).

## Best result
Tuned Logistic Regression – F1 = 0.620, Recall = 0.644, Accuracy = 0.790

## How to run
1. Open `Telco_Churn_Coursework.ipynb` in Google Colab.
2. Run all cells (the dataset is loaded automatically from IBM's public GitHub,
   or upload `WA_Fn-UseC_-Telco-Customer-Churn.csv` from Kaggle).

## Files
- `Telco_Churn_Coursework.ipynb` – full notebook (EDA, preprocessing, models, evaluation, ethics check)
- `telco_churn.py` – same code as a Python script
