# 🏦 Banking Loan Analytics Project | 30,000 Loan Records

## 📌 Project Overview
This project analyzes **30,000 banking loan applications** from 2023-2026. The goal was to understand loan approval trends, identify risk factors, analyze customer payment behaviour, and provide data-driven recommendations to reduce defaults and improve profitability.

The dataset contains customer demographics, financial details, loan details, and repayment status.

**File:** `Banking_Loan_Analytics_30000.xlsx`
**Total Records:** 30,000 | **Sheets:** 3 (Raw_Data, Data_Dictionary, Starter_KPIs)

---

## 🎯 Business Problem
Bank wants to answer:
1.  Which loan types are most in demand?
2.  What is the approval vs rejection rate and why?
3.  How many customers are defaulting and in which segment?
4.  Which risk category needs strict monitoring?

## 🛠️ Tools & Techniques Used
- **Advanced Excel:** XLOOKUP, VLOOKUP, IF, IFS, COUNTIFS, SUMIFS, AVERAGEIFS, TRIM, PROPER
- **Pivot Tables & Slicers:** For dynamic summary
- **Charts & Dashboard:** Pie, Bar, Column, Donut charts
- **Data Cleaning:** Removed inconsistencies, created Age_Group & Income_Group buckets
- **Conditional Formatting:** For Risk Category highlighting

---

## 📊 Key KPIs

| KPI | Value |
| :--- | :--- |
| Total Applications | 30,000 |
| Approved | 20,903 (69.7%) |
| Outstanding Amount | 26.8M |
| Interest Rate% | 304K |
| Total Loans | 50.5M |
| Avg Credit Score | 714.6|
| EMI | 833M|

---

## 💡 Detailed Insights

### 1. Loan Type Demand
- **Personal Loan - 10,567 (35.2%)** - Highest demand. Customers take small-ticket loans for personal needs. Easy to process.
- **Home Loan - 7,452 (24.8%)** - Second highest, long-tenure and high value.
- **Auto Loan - 5,396 (18%)** - Stable segment.
- **Business & Education Loan - ~22% combined** - Low volume due to strict eligibility.

> **Insight:** Personal loan is volume driver, Home loan is value driver.

### 2. Application Status - Approval Analysis
- **69.7% Approval** - Shows bank is balanced, not too strict not too lenient.
- Rejection of 30.3% is mainly due to low Credit Score (<650) and high Debt-to-Income >45%.

### 3. Risk Category Analysis
- **Medium Risk: 12,979 (43%)** - Core portfolio. Needs standard monitoring.
- **High Risk: 11,256 (38%)** - Very high number! This is alarming. These customers have lower credit scores and multiple existing loans.
- **Low Risk: 5,765 (19%)** - Premium customers. Bank should retain them with better interest rates.

> **Insight:** 38% High-Risk portfolio is risky. Bank must tighten approval for High-Risk.

### 4. Payment Behaviour & Default
- **On-Time: 13,760** - Good repayment culture.
- **Late Payment: 4,634** - 22% of approved customers pay late (30-60 days). They need reminder system.
- **Overdue + Defaulted: 2,509 (12%)** - This is loss-making segment.
- **Overall Default Rate 2.75%** is under control (industry standard 3-4%), but still 824 loans are complete loss.

**Default is highest in:** Personal Loan & Business Loan (because collateral nahi hota)

### 5. Customer Demographics
- Most customers are from 30-50 age group (working population)
- Self-employed customers have higher rejection compared to Salaried
- Partner channel brings more High-Risk applications

---

## ✅ Conclusion

1.  Bank is doing well with 69.7% approval and only 2.75% default rate.
2.  Personal Loan is driving business volume but also has higher default chances.
3.  High-Risk category (38%) is too large and needs immediate attention.
4.  Late payments (22%) show need for better collection process.
5.  Data is clean and shows real banking scenario of Active, Closed, Overdue loans.

---

## 🚀 Recommendations

1.  **Tighten High-Risk Approval:** Credit score cut-off should be increased from 650 to 680 for Personal/Business loans.
2.  **Focus on Low-Risk Customers:** Offer 0.5% lower interest to Low-Risk customers for retention.
3.  **Improve Collection:** Auto-reminder SMS/Email 3 days before EMI for Late payers (4,634 customers).
4.  **Partner Channel Audit:** Partner se aane wale loans me default zyada hai, commission structure change karo.
5.  **Promote Secured Loans:** Home & Auto loan (with collateral) pe focus badhao, kyunki inka default kam hai.

---

## 📂 How to Use

1.  Download `Banking_Loan_Analytics_30000.xlsx`
2.  Open `Raw_Data` sheet - 30,000 rows
3.  Check `Starter_KPIs` for summary
4.  Use Filters on Risk_Category, Loan_Type to explore

## 📸 Dashboard
<img src="dashboard1.png" width="100%"><br><br>

---
**Created By:** [Khan Saquib Alam] | **Domain:** Banking Analytics | **Tool:** Advanced Excel
