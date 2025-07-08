# Telecom-Churn-Prediction
Machine learning project to predict customer churn for a telecom company using classification models and feature engineering.
# 📞 Telecom Churn Prediction

This project analyzes customer data from a telecom company to **predict churn** — the likelihood that a customer will leave the service. By identifying these customers in advance, telecom providers can implement retention strategies to reduce churn and improve profitability.

---

## 📌 Problem Statement

Customer churn is a critical business issue in the telecom industry. This project aims to:
- Analyze the factors that influence churn.
- Build a predictive model to classify customers as likely to churn or not.
- Help telecom companies make data-driven decisions for customer retention.

---

## 📂 Dataset Overview

The dataset contains information on **customer demographics**, **service subscriptions**, and **billing details**. Key features include:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `InternetService`
- `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`
- Target variable: `Churn`

📁 *Dataset Source*: (Mention if from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn), company, or internship)

---

## 🧪 Methodology

1. **Data Preprocessing**
   - Handling missing and inconsistent values
   - Encoding categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Churn rate across contract types, payment methods, tenure
   - Correlation heatmaps
   - Distribution plots and customer segmentation

3. **Feature Engineering**
   - Binning tenure
   - Derived metrics like `charges_per_month` or `service_count`

4. **Model Building**
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - XGBoost

5. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - ROC-AUC Curve
   - Confusion Matrix

---

## 🧠 Key Findings

- Customers with month-to-month contracts, higher charges, and short tenure are more likely to churn.
- Long-term contract customers show significantly lower churn rates.
- Payment methods (e.g., electronic check) correlate strongly with churn behavior.
