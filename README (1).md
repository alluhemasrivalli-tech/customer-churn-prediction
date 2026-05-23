# 📊 Customer Churn Prediction — End-to-End Data Science Project

> **IBM Python for Data Science Certificate Project**  
> **Author:** Allu Hema Srivalli  
> **Date:** May 2026

---

## 🎯 Problem Statement

A telecom company is losing customers (churning). This project:
1. **Understands** why customers leave using Exploratory Data Analysis
2. **Predicts** which customers are likely to churn using Machine Learning
3. **Recommends** business actions to reduce churn

---

## 📁 Project Structure

```
customer-churn-project/
│
├── Customer_Churn_Prediction.ipynb   ← Main Jupyter Notebook
├── Telco-Customer-Churn.csv          ← Dataset (IBM Telco)
├── README.md                         ← This file
│
└── charts/
    ├── churn_distribution.png
    ├── contract_tenure_analysis.png
    ├── charges_internet_analysis.png
    ├── correlation_heatmap.png
    ├── model_evaluation.png
    └── feature_importance.png
```

---

## 🔍 Dataset

- **Source:** IBM Telco Customer Churn (via Kaggle)
- **Size:** 7,043 customers × 21 features
- **Target:** `Churn` (Yes/No)

---

## 📈 Key Findings

| # | Insight | Churn Rate |
|---|---------|------------|
| 1 | Month-to-month contract customers | **42.7%** |
| 2 | Two-year contract customers | **2.8%** |
| 3 | Fiber optic internet users | **41.9%** |
| 4 | Customers in first 12 months | **Highest risk** |

---

## 🤖 Model Performance

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | **79.91%** | **0.8403** |
| Decision Tree | 78.50% | 0.8217 |

---

## 🛠️ Tools & Libraries

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/customer-churn-prediction.git
cd customer-churn-prediction

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch notebook
jupyter notebook Customer_Churn_Prediction.ipynb
```

---

## 💼 Business Recommendations

1. **Incentivize long-term contracts** — offer discounts to convert monthly customers to annual plans
2. **Early intervention program** — proactively reach out to customers in their first 6 months
3. **Fiber optic pricing review** — investigate why fiber users churn at 42% and address root cause
4. **Tiered pricing strategy** — reduce perceived value gap for high-paying customers

---

## 🏅 Certificate

This project was built as part of the **IBM Python for Data Science** course, completed May 2026.  
Verify: https://www.credly.com/badges/f39fa7ff-b2c2-4bef-8dae-a161153efbe5

