# CreditwWise-Loan-Approval-System

## 📌 Project Overview
The **CreditWise Loan Approval System** is a Machine Learning–based project designed to automate loan approval decisions for a financial institution.  
The system analyzes applicant financial, credit, and demographic data to predict whether a loan should be **Approved or Rejected**, helping reduce manual effort, bias, and financial risk.

---

## 🎯 Business Problem
Traditional loan approval processes rely heavily on manual verification, which is:
- Time-consuming
- Inconsistent
- Prone to human bias

This leads to two major issues:
1. **Good customers get rejected**, resulting in business loss  
2. **High-risk customers get approved**, causing financial losses  

This project aims to solve these problems using data-driven decision-making.

---

## 🗂 Dataset Description
Each record in the dataset represents a loan applicant with the following key attributes:

- Applicant Income & Co-applicant Income  
- Employment Status  
- Age, Marital Status, Dependents  
- Credit Score  
- Existing Loans  
- Debt-to-Income (DTI) Ratio  
- Savings & Collateral Value  
- Loan Amount & Loan Term  
- Loan Purpose  
- Property Area  
- Education Level  
- Gender  
- **Loan_Approved (Target Variable)**  

Target:
- `1` → Loan Approved  
- `0` → Loan Rejected  

---

## ⚙️ Technologies Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🧠 Machine Learning Models Implemented
- Logistic Regression  
- Random Forest Classifier  
- (Optional / Future) XGBoost  

Model performance was compared to select the most reliable classifier.

---

## 📊 Evaluation Metrics
To ensure business reliability, multiple metrics were used:
- Accuracy
- Precision
- Recall
- F1-Score

Special focus was given to **reducing false approvals of high-risk applicants**.

---

## 📈 Key Insights
- Credit Score and DTI Ratio are the strongest predictors of loan approval
- Applicants with multiple existing loans have a higher rejection probability
- Higher collateral value improves approval chances
- ML-based decisions are more consistent than manual verification

---

## 🚀 Future Enhancements
- Deployment using **Flask / FastAPI**
- Real-time loan approval API
- Explainable AI using **SHAP**
- Dashboard integration for business users

---

## 📄 Project Report
A detailed project report is available in the `docs/` folder.

---

## 👤 Author
**Utkarsh Bachhav**  
📧 Email: utkarshbachhav08@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/your-linkedin-username  
💻 GitHub: https://github.com/your-github-username  

---

⭐ If you found this project useful, feel free to star the repository.
