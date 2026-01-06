## Customer Churn Analysis & Prediction — Power BI + Python Project

## 💡 Project Summary
This project analyzes telecom customer churn using **Power BI** for business insights and **Python Machine Learning** to predict churn probability at a customer level.

The goal is to help businesses:
- Identify **why customers churn**
- Detect **high-risk customers early**
- Support **targeted retention strategies**

---

## 📂 Dataset
**Source:** Kaggle — Telco Customer Churn  
Contains 7,043 customer records with demographics, billing, services, and contract data.

---

## 🛠 Tech Stack
- Power BI
- Python (pandas, scikit-learn)
- DAX Measures
- CSV / Excel
- Kaggle Dataset

---

## 🚀 Project Workflow

### 1️⃣ Data Cleaning
- Converted `TotalCharges` to numeric
- Handled missing values
- Created churn flag

### 2️⃣ Churn Analysis (Power BI)
- Churn Rate %
- Churn by Contract, Internet Service, Payment Method
- Avg Tenure & Charges comparison

### 3️⃣ Churn Prediction (Python)
- Logistic Regression Model
- Features:
  - tenure, MonthlyCharges, TotalCharges
  - Contract, InternetService, PaymentMethod
- Output:
  - `ChurnProbability`
  - `ChurnPredicted`
- Exported → `Telco_Churn_Predictions.csv`

### 4️⃣ Power BI Prediction Dashboard
- Integrated prediction file
- Built **risk segmentation dashboard**
  - High Risk (≥ 0.70)
  - Medium Risk (0.40–0.69)
  - Low Risk (< 0.40)

---

## 📸 Dashboard Screenshots
> *(Add your images here)*


---

## 📁 Project Structure
├── data/
│ ├── Telco-Customer-Churn.csv
│ ├── Telco_Churn_Predictions.csv
├── notebooks/
│ ├── churn_model.ipynb
├── powerbi/
│ ├── Churn_Dashboard.pbix
├── REPORT.md
└── README.md

---

## 📌 Key Insights
- Month-to-month contracts churn the most
- Higher monthly charges increase churn risk
- Early-tenure customers are vulnerable
- Lack of support services leads to exits

---

## 🎯 Business Recommendations
- Convert customers to **long-term contracts**
- Target **high-risk groups with retention offers**
- Improve onboarding & engagement programs
- Bundle support/security services

---

## 🌱 Future Enhancements
- Real-time scoring
- CLV integration
- XGBoost churn model
- CRM automation

---

## 🧑‍💻 Author
MBA — Business Analytics | Power BI | Python

---



