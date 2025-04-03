# 🏦 Loan Default Prediction

## 💼 Overview
This project builds a machine learning model to predict loan default risk using historical financial data. The goal is to help lenders better assess risk and reduce losses—especially relevant to fintech and financial institutions.

## 🧠 Problem Statement
Loan defaults pose a major risk to financial institutions. By accurately identifying high-risk applicants, businesses can make informed credit decisions, reduce risk exposure, and improve financial performance.

## 📊 Dataset
- **Source**: LendingClub loan data (public dataset via Kaggle)
- **Features**: Loan amount, interest rate, income, credit score, employment length, loan purpose, and more
- **Target**: Loan status (Fully Paid vs Charged Off)

## ⚙️ Techniques Used
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Handling class imbalance with **SMOTE**
- Feature engineering
- Model training: **Logistic Regression**, **Random Forest**, **XGBoost**
- Evaluation metrics: **AUC**, **F1-score**, **Precision/Recall**
- Model explainability using **SHAP**
- Visualisation using **Seaborn & Matplotlib**

## ✅ Results
- Best model: XGBoost with AUC = 0.92  
- SHAP insights revealed top predictive features like interest rate and loan amount  
- Built foundation for risk-scoring dashboard using Power BI (future extension)

## 🛠 Tools & Tech
Python, Pandas, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn, Jupyter

## 📈 Business Impact
With this predictive model, financial institutions can:
- Improve loan approval decisions
- Reduce bad debt write-offs
- Gain insight into high-risk customer profiles

## 🚀 Next Steps
- Integrate model into a simple dashboard
- Automate retraining pipeline with new loan data
- Explore credit scoring fairness and ethical considerations

---

🔗 **Note**: Code and model notebook will be uploaded soon.
