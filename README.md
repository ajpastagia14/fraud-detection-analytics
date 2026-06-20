# Fraud Detection Analytics

## Project Overview

This project analyzes financial transaction data to identify patterns associated with fraudulent activity and build machine learning models capable of detecting potentially fraudulent transactions.

The project covers the complete analytics workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, visualization, model development, and performance evaluation.

---

## Business Problem

Financial institutions process thousands of transactions every day, making it difficult to manually identify suspicious activity.

The objective of this project was to:

* Detect potentially fraudulent transactions
* Understand behavioral differences between legitimate and fraudulent transactions
* Identify the most influential fraud indicators
* Build machine learning models to support fraud detection efforts

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Dataset Overview

The dataset contains transaction-level information, including:

* Transaction Amount
* Customer Age
* Distance From Home
* Number of Items Purchased
* Device Type
* Network Quality
* Previous Transactions
* Transaction Time
* Velocity Score
* Fraud Status

Target Variable:

* 0 = Legitimate Transaction
* 1 = Fraudulent Transaction

---

## Data Cleaning & Preparation

The following preprocessing steps were performed:

* Missing value analysis
* Median imputation for numerical variables
* Data validation checks
* Feature preparation for modeling
* Train-test split using stratified sampling

---

## Exploratory Data Analysis

Key analyses included:

* Fraud distribution analysis
* Transaction amount comparison
* Customer behavior analysis
* Distance from home investigation
* Velocity score evaluation
* Correlation analysis
* Feature importance analysis

Several visualizations were created to understand fraud patterns and transaction behavior.

---

## Machine Learning Models

### Logistic Regression

Used as a baseline classification model to establish initial performance metrics.

### Random Forest Classifier

A Random Forest model was trained to improve fraud detection performance and identify the most influential predictive variables.

Model evaluation included:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Feature Importance Analysis

---

## Key Findings

* Fraudulent transactions represented approximately 11% of all transactions.
* Distance from home was one of the strongest indicators of fraudulent activity.
* Transaction amount and velocity score showed significant influence on fraud prediction.
* Class imbalance affected model performance and required careful evaluation.
* Random Forest outperformed the baseline model and provided better feature interpretability.

---

## Business Recommendations

Based on the analysis:

* Flag transactions occurring unusually far from a customer's typical location.
* Monitor high-value transactions more closely.
* Incorporate velocity-based monitoring for rapid transaction activity.
* Combine multiple behavioral indicators to improve fraud detection accuracy.

---

## Project Structure

```text
fraud-detection-analytics/
│
├── README.md
├── fraud.csv
├── fraud_cleaned.csv
├── fraud_detection_analysis.ipynb
├── fraud_visualization_analysis.ipynb
└── screenshots/
```

---

## Author

Akshar Pastagia

GitHub: https://github.com/ajpastagia14

LinkedIn: https://www.linkedin.com/in/akshar-pastagia-228203269/
