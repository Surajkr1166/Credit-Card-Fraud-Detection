# Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions on a highly imbalanced dataset.

## Dataset
- 284,807 transactions with only 0.17% fraud rate
- Features: transaction amount, time, and anonymized PCA components

## What I Did
- Performed EDA and data cleaning to understand fraud patterns
- Handled class imbalance using SMOTE and Random Oversampling
- Trained multiple ML models: Logistic Regression, Random Forest, XGBoost, SVM, KNN
- Used Stratified K-Fold Cross Validation for reliable evaluation
- Achieved ROC-AUC of 0.98

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, imbalanced-learn

## Results
| Model | ROC-AUC |
|-------|---------|
| Random Forest | 0.98 |
| XGBoost | 0.97 |
| Logistic Regression | 0.95 |
