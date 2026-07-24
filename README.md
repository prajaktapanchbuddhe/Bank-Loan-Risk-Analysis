# 🏦 Bank Loan Risk Analysis

## 📌 Project Overview

This project analyzes customer loan data to identify the key factors influencing loan default. Using Python, exploratory data analysis (EDA), statistical analysis, and a Random Forest machine learning model, the project uncovers patterns that can help financial institutions improve credit risk assessment and lending decisions.

---

## 🎯 Business Problem

Loan defaults result in significant financial losses for banks and lending institutions. The objective of this project is to analyze customer characteristics, identify the major factors associated with loan default, and provide actionable business recommendations based on data-driven insights.

---

## 📂 Dataset Overview

- **Total Records:** 255,347
- **Total Features:** 18
- **Target Variable:** Default
- **Default Rate:** 11.61%
- **Non-Default Rate:** 88.39%

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

- Data Loading & Exploration
- Data Cleaning & Validation
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Random Forest Feature Importance
- Business Insights
- Executive Summary
- Business Recommendations

---

## 📈 Key Findings

- 💰 Income was the most important predictor of loan default.
- 💳 Higher loan amounts were associated with a greater risk of default.
- 📉 Customers with higher interest rates showed a higher likelihood of default.
- 💼 Longer employment history reduced default risk.
- 📊 Credit Score showed limited linear correlation but remained an important feature in the Random Forest model.
- 👨‍👩‍👧‍👦 Mortgage status, dependents, and co-signer information had relatively low predictive importance.

---

## 🤖 Machine Learning

A **Random Forest Classifier** was used to identify the most influential features contributing to loan default prediction.

Top Important Features:

1. Income
2. Interest Rate
3. Loan Amount
4. Credit Score
5. Age
6. Months Employed

---

## 💼 Business Recommendations

- Prioritize customer income during credit evaluation.
- Apply additional risk assessment for larger loan amounts.
- Monitor customers with higher interest rates more closely.
- Consider employment history and financial stability during loan approval.
- Use machine learning models alongside traditional credit assessment techniques to improve lending decisions.

---

## 📸 Project Screenshots

### 📊 Loan Default Distribution

This chart shows the distribution of customers who defaulted versus those who repaid their loans. The dataset is imbalanced, with approximately **88% non-defaults** and **12% defaults**.

![Loan Default Distribution](images/default_distribution.png)

---

### 💰 Income Analysis

Customers with lower average incomes were more likely to default. Income emerged as one of the strongest predictors of loan default.

![Income Analysis](images/income_analysis.png)

---

### 💳 Loan Amount Analysis

Customers with larger loan amounts showed a higher probability of default, indicating that loan size plays an important role in credit risk.

![Loan Amount Analysis](images/loan_amount_analysis.png)

---

### 🤖 Feature Importance

A Random Forest model was used to rank the importance of different variables. Income, Interest Rate, Loan Amount, Credit Score, and Months Employed were among the most influential features.

![Feature Importance](images/feature_importance.png)

---

## 📁 Repository Structure

```text
Bank-Loan-Risk-Analysis/
│
├── Data/
├── Images/
├── loan_analysis.ipynb
└── README.md
```

---

## 👩‍💻 Author

**Prajakta Panchbuddhe**

Aspiring Data Analyst

**Skills:** SQL • Python • Power BI • Excel • Machine Learning

---

⭐ If you found this project interesting, feel free to explore the notebook and connect with me on LinkedIn!
