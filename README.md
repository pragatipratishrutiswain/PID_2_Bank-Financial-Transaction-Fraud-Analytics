# PID_2_Lending Prediction & Risk Analytics

## 📌 Full-stack Financial Lending Analytics | Default Risk Modeling | Power BI Dashboards | Banking Sector

## 📖 Table of Contents

🔍 Project Overview
  
🧩 Business Objectives
  
📊 KPIs Tracked
  
🗂️ Dataset Details
  
🏛️ System Architecture
  
🧪 Data Processing & Feature Engineering
  
🤖 Machine Learning Models
  
📈 Results & Insights
  
📊 Power BI Dashboards
  
📁 Repository Structure
  
🚀 How to Run
  
🔮 Future Enhancements
  
👤 Author


## 🔍 Project Overview

This project focuses on end-to-end lending analytics — enabling financial institutions to improve loan approval decisions and manage credit risk effectively.
It combines:

✔ Data preprocessing & SQL-based validation
✔ Predictive modeling for approval and default risks
✔ MTD & MoM financial performance analysis
✔ Business dashboards for leadership decisions



## 🧩 Business Objectives

Predict Loan Approval likelihood

Predict Loan Default risk

Reduce NPAs (Non-Performing Assets)

Identify high-risk borrower profiles

Enhance credit policy decisions with analytics

Improve lending portfolio health and operational efficiency


## 📊 KPIs Tracked
| Metric                        | Description                       | Trend                |
| ----------------------------- | --------------------------------- | -------------------- |
| **Total Loan Applications**   | MTD count and MoM comparison      | Volume & demand      |
| **Total Funded Amount**       | Approved loan disbursement trends | Capital allocation   |
| **Total Amount Received**     | Cash inflow from repayments       | Liquidity & recovery |
| **Average Interest Rate**     | Overall pricing health            | Revenue generation   |
| **Avg. Debt-to-Income Ratio** | Applicant financial risk level    | Creditworthiness     |



## 🗂️ Dataset Details

Source: Synthetic internal-style Banking Dataset

Records: Loan applicants with repayment outcomes

### Key Fields

1. id
2. address_state
3. application_type
4. emp_length
5. emp_title
6. grade
7. home_ownership
8. issue_date
9. last_credit_pull_date
10. last_payment_date
11. loan_status
12. next_payment_date
13. member_id
14. purpose
15. sub_grade
16. term
17. verification_status
18. annual_income
19. dti (debt to interest ratio)
20. installment
21. int_rate
22. loan_amount
23. total_acc
24. total_payment

## 🏛️ System Architecture

Excel Source → SQL Validation → Python (Colab) → EDA & ML → Power BI → Dashboards

## 🧪 Data Processing & Feature Engineering

1. Handling missing values & outliers
2. Feature encoding: Grade, Home Ownership, Employment Length
3. Date transformation for MTD & MoM analysis
4. Imbalanced data handling (loan default)
5. Feature importance analysis

## 🤖 Machine Learning Models
| Model                        | Purpose                 | Role                                 |
| ---------------------------- | ----------------------- | ------------------------------------ |
| **Logistic Regression**      | Baseline classification | Benchmark & interpretability         |
| **Random Forest Classifier** | Final selected model    | Best accuracy & balanced performance |
| **XGBoost**                  | Optimization            | Performance tuning                   |

📌 Random Forest performed best and is used in final predictions.

## 📈 Results & Insights

Performance metrics such as Accuracy, F1-Score, ROC-AUC to be updated after model evaluation.
Dashboard insights reveal high default risk patterns among:

Low-income borrowers with higher DTI

Lower credit grade categories

Applicants from high-risk states

Long-term loans (> 36 months)

## 📊 Power BI Dashboards

📌 MTD/MoM Lending KPIs | Approval Analytics | Default Risk Map

🔗 Live Report: (Add your Power BI link here)

🖼️ Screenshots: (Insert images)

## 📁 Repository Structure

|-- data/    
|-- notebooks/
|   └── Lending_Risk_Model.ipynb
|-- dashboards/
|   └── PowerBI_Screenshots/
|-- src/
|   └── preprocessing.py
|   └── modeling.py
|-- README.md (this file)

🚀 How to Run

### Clone repo
git clone https://github.com/<your-username>/lending-risk-analytics.git
cd lending-risk-analytics

### Install dependencies
pip install -r requirements.txt

### Open notebook
colab notebook /Lending_Risk_Model.ipynb

## 🔮 Future Enhancements

Add credit score bureau validation

Deploy ML model as API for loan scoring

Streamlit dashboard integration

Model explainability (SHAP)

Real-time approval pipeline automation

## 👤 Author

Your Name — Full-Stack Data Analytics | FinTech

📧 Email: pragati.pratishruti@gmail.com

🔗 LinkedIn: www.linkedin.com/in/pragatipratishrutiswain
