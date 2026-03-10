# Bank Customer Churn Prediction using Machine Learning

This project builds machine learning models to predict whether a bank customer will leave the bank (churn) based on demographic and financial attributes.

The goal is to identify customers at risk of leaving so banks can implement targeted retention strategies.

---

## Dataset Overview

The dataset contains information about **10,000 bank customers** and whether they exited the bank.

Key features include:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Account Balance
- Number of Products
- Active Membership Status
- Estimated Salary

### Target Variable

Exited  
0 → Customer stayed  
1 → Customer churned

---

## Project Workflow

1. Data Inspection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Feature Importance Analysis

---

## Models Used

### Logistic Regression
Baseline classification model.

Accuracy: **81%**

### Random Forest Classifier
Ensemble model capable of capturing complex relationships.

Accuracy: **87%**

---

## Feature Importance

The most important features influencing customer churn were:

- Age
- Account Balance
- Estimated Salary
- Number of Products
- Credit Score

---

## Key Insights

- Customer churn is **imbalanced**, with most customers staying.
- Older customers showed a higher tendency to churn.
- Customers with higher balances showed increased churn risk.
- Random Forest significantly outperformed Logistic Regression.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Model File

The trained Random Forest model is saved as:

models/churn_prediction_model.pkl
This allows the model to be reused without retraining.

---

## Conclusion

Machine learning models can help financial institutions identify high-risk customers and develop strategies to improve customer retention.

Random Forest achieved the best performance with **87% accuracy**.

---

## Author
Joemon
