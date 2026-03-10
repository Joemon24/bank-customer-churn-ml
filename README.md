# Bank Customer Churn Prediction using Machine Learning

This project builds machine learning models to predict whether a bank customer will leave the bank (churn) based on demographic and financial attributes.

The goal is to identify customers at risk of leaving so banks can implement targeted retention strategies.

---

## Dataset

The dataset used in this project is publicly available on Kaggle.

Download it here:

https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction

After downloading, place **Churn_Modelling.csv** inside the project folder before running the notebook.

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
## How to Run

1. Install dependencies
```bash
pip install -r requirements.txt
```
2. Download the dataset from Kaggle.

3. Place **Churn_Modelling.csv** in the project folder.

4. Run the notebook:
```
jupyter notebook "Bank Customer Churn.ipynb"
```
---
## Conclusion

Machine learning models can help financial institutions identify high-risk customers and design targeted retention strategies.

Random Forest achieved the best performance with **87% accuracy**.

---

## Author

Joemon
