# 📊 Bank Loan Analysis Dashboard | Power BI

## 📌 Project Overview
This project is an interactive Power BI dashboard developed to analyze bank loan data and provide insights into:

- Loan applications
- Funded amounts
- Amount received
- Good vs Bad loans
- Borrower demographics
- Loan purposes
- Geographic loan distribution
- Monthly trends

The dashboard helps in understanding loan performance, repayment behavior, and borrower risk segmentation using powerful visual analytics and DAX calculations.

---

# 🚀 Features

## ✅ Summary Dashboard
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI
- Good Loan vs Bad Loan Analysis
- Loan Status Summary Table

---

## ✅ Overview Dashboard
- Monthly Loan Application Trends
- State-wise Loan Distribution
- Loan Applications by Term
- Home Ownership Analysis
- Employee Length Analysis
- Loan Purpose Analysis

---

## ✅ Details Dashboard
- Detailed loan-level records
- Borrower and loan attributes
- Filtering and drill-down capabilities

---

# 🛠️ Tools & Technologies Used

- Power BI
- DAX (Data Analysis Expressions)
- Power Query
- Data Visualization
- Financial Analytics

---

# 📂 Dataset Information

The dataset contains information related to:
- Loan applications
- Funded amounts
- Interest rates
- DTI ratios
- Loan statuses
- Home ownership
- Employment length
- Loan purposes
- State-level borrower data

---

# 📊 Key DAX Measures Used

```DAX
Total Loan Applications = COUNT(financial_loan[id])

Total Funded Amount = SUM(financial_loan[loan_amount])

Total Amount Received = SUM(financial_loan[total_payment])

Avg Interest Rate = AVERAGE(financial_loan[int_rate]) * 100

Avg DTI = AVERAGE(financial_loan[dti]) * 100
```

---

# 🎯 Business Insights

- Majority of loans are classified as Good Loans
- Debt Consolidation is the most common loan purpose
- 36-month loans are more frequent than 60-month loans
- Certain states show higher loan application volumes
- Borrowers with longer employment history apply more frequently

---

# 📁 Repository Structure

```text
├── Bank_Loan_Report.pbix
├── financial_loan.csv
├── Summary_Page.png
├── Overview_Page.png
├── Details_Page.png
└── README.md
```

---

# 💡 Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX Calculations
- Dashboard Design
- KPI Reporting
- Financial Data Analysis
- Business Intelligence

---

# 👨‍💻 Author

Vishal

---

# ⭐ If you like this project
Please give this repository a star ⭐