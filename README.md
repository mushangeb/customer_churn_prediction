# 📈 Customer Churn Prediction - Telecom Industry

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)
![ML](https://img.shields.io/badge/Machine%20Learning-Sklearn-yellow)

> Predict customer churn using machine learning to help telecom providers improve customer retention.

---

## 🧠 Problem Statement

Customer churn—when customers stop using a service—is a major challenge in the telecom industry. The goal of this project is to analyze customer behavior and predict churn based on historical service and demographic data.

---

## 📁 Dataset Overview

- **Name**: Telco Customer Churn Dataset
- **Size**: 1,000 records
- **Format**: CSV
- **Target Variable**: `Churn` (Yes/No)

### 📌 Key Features
| Feature           | Description                                      |
|-------------------|--------------------------------------------------|
| `CustomerID`      | Unique identifier                                |
| `Tenure`          | Customer duration (in months)                    |
| `ContractType`    | Month-to-Month, One Year, Two Year               |
| `MonthlyCharges`  | Monthly service charges                          |
| `TotalCharges`    | Total amount billed                              |
| `TechSupport`     | Availability of tech support                     |
| `InternetService` | Type of internet service (DSL/Fiber/None)        |
| `Churn`           | Whether the customer has left the service        |

---

## 🧰 Tech Stack

- **Language**: Python
- **Libraries**:
  - pandas, numpy
  - matplotlib, seaborn
  - scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)

- Distribution of churn vs. non-churn customers
- Impact of contract type, tenure, and billing on churn
- Visualizations with Seaborn and Matplotlib

---

## 🤖 Machine Learning Models

| Model               | Purpose                    |
|---------------------|----------------------------|
| Logistic Regression | Baseline classification    |
| Random Forest       | Improved performance       |

### ✅ Evaluation Metrics

- Accuracy
- Precision & Recall
- Confusion Matrix

---

## 📈 Results

- The Random Forest model outperformed Logistic Regression.
- Features like `ContractType`, `Tenure`, and `TotalCharges` were the most predictive.

## 🚀 Getting Started

1. Clone the repository or download the notebook:
   ```bash
   git clone https://github.com/mushangeb/customer_churn_prediction.git
