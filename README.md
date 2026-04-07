# 🚨 Fraud Detection in Online Transactions

A machine learning project focused on detecting fraudulent financial transactions using behavioral patterns and anomaly detection techniques.

This project simulates how banks can identify suspicious transactions in real-time to reduce financial losses and strengthen fraud risk management.

---

## 📌 Business Problem

Fraudulent transactions pose a significant risk to financial institutions, leading to revenue loss, reputational damage, and regulatory challenges.

The objective of this project is to build a predictive model that can accurately identify fraudulent transactions from large volumes of transaction data.

By detecting fraud early, the bank can:

- prevent financial losses
- improve fraud monitoring systems
- enhance customer trust
- reduce manual investigation workload

---

## 🎯 Project Objectives

- perform exploratory data analysis (EDA)
- identify patterns in fraudulent behavior
- handle imbalanced transaction data
- build fraud detection models
- evaluate model performance using appropriate metrics
- generate actionable insights

---

## 📊 Dataset Overview

The dataset used for this project contains records of online transactions, each labeled as fraudulent or legitimate. It includes features such as transaction amount, payment method, location, and time of transaction. The dataset is cleaned, preprocessed, and split into training and testing sets to develop and evaluate the models.

Dataset link: Kaggle link https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection
An example of the data structure:

1,PAYMENT,9839.64,C1231006815,170136.0,160296.36,M1979787155,0.0,0.0,0,0
1,PAYMENT,1864.28,C1666544295,21249.0,19384.72,M2044282225,0.0,0.0,0,0

The dataset contains transaction-level data including:

- transaction amount
- transaction type
- account balances (before and after transaction)
- transaction time
- fraud label

### Target Variable
> **is_fraud**

- `0 = Legitimate Transaction`
- `1 = Fraudulent Transaction`

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Imbalanced-learn (SMOTE)  
- Jupyter Notebook  

---

## 🔍 Exploratory Data Analysis

EDA was conducted to understand patterns that distinguish fraudulent transactions.

### Key Findings
- Fraud cases are extremely rare, confirming a highly imbalanced dataset
- Fraudulent transactions exhibit unusual transaction amounts
- Certain transaction types are more prone to fraud
- Time-based patterns indicate behavioral anomalies
- Balance inconsistencies are strong indicators of fraud

---

## ⚙️ Modeling Approach

The problem is approached as a **binary classification task**.

### Key Steps
- Data preprocessing and feature engineering  
- Handling class imbalance using **SMOTE**  
- Train-test split  
- Model training  

### Models Used
- Logistic Regression  
- Random Forest Classifier  

---

## 📈 Model Performance

### Evaluation Metrics
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

### Key Focus
Fraud detection prioritizes **recall**, as failing to detect fraudulent transactions results in direct financial loss.

---

## 💡 Key Insights

### 1. Transaction Amount
Abnormal transaction values are strong indicators of fraud.

### 2. Transaction Behavior
Irregular balance changes often signal suspicious activity.

### 3. Transaction Type
Certain transaction channels are more vulnerable to fraud.

---

## 🏦 Banking Use Case

This project can be applied in banking systems such as NCBA for:

- real-time fraud detection  
- transaction monitoring systems  
- anomaly detection pipelines  
- automated fraud alerts  

This supports proactive risk management and improved operational efficiency.

---

## 🚀 Future Improvements

- XGBoost / LightGBM models  
- real-time deployment using APIs  
- threshold tuning for risk tolerance  
- integration with fraud monitoring dashboards  

---

## 👩‍💻 Author

**Joy Achieng Odhiambo**  
Data Scientist 
GitHub: https://github.com/AchiengJoy
