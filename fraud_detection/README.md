# Fraud Detection Analytics Project

## Project Overview

This project focuses on detecting fraudulent financial transactions using:

- Python
- Pandas
- Seaborn
- Machine Learning
- Exploratory Data Analysis (EDA)

The goal was to analyze transaction behavior, identify fraud patterns, handle missing values, engineer behavioral features, and build predictive fraud detection models.

---

## Dataset Information

The dataset contains transaction-level financial data including:

- transaction amount
- customer age
- number of items
- transaction timing
- distance from home
- network quality
- device type
- velocity score
- fraud status

Target Variable:
- `0` = Legitimate Transaction
- `1` = Fraudulent Transaction

---

## Data Cleaning

Performed:
- missing value analysis
- median imputation for numerical columns
- mode imputation for categorical columns
- missing value flag creation
- dataset validation

---

## Exploratory Data Analysis (EDA)

Analyzed:
- fraud distribution
- transaction amount patterns
- distance from home behavior
- transaction timing behavior
- velocity score patterns
- correlation heatmap
- engineered fraud indicators

Created behavioral features:
- `high_amount_flag`
- `far_from_home_flag`
- `high_risk_behavior`

---

## Machine Learning

Models used:
- Logistic Regression
- Balanced Logistic Regression

Techniques applied:
- train-test split
- class imbalance handling
- confusion matrix evaluation
- precision / recall analysis

---

## Key Findings

- Fraud cases represented approximately 11% of transactions.
- Fraudulent transactions showed slightly higher behavioral risk patterns.
- Class imbalance significantly impacted model performance.
- Balanced Logistic Regression improved fraud detection recall.

---

## Project Structure

```text
fraud-detection-analytics/
│
├── fraud.csv
├── fraud_cleaned.csv
├── fraud_analysis.ipynb
└── README.md
```

---

## Future Improvements

Planned next steps:
- SQL analytics phase
- Tableau dashboard development
- Random Forest implementation
- Feature scaling
- SMOTE balancing
- Model optimization

---

## Author

Akshar Pastagia

GitHub:
https://github.com/ajpastagia14