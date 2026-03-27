# 💳 Credit Card Customer Segmentation

Data cleaning and preparation of credit card and user datasets for 
RevoBank Indonesia to support customer segmentation and sales performance analysis.

**Program:** RevoU Full Stack Data Analytics — Python Module  
**Period:** Nov 2025

---

## 🎯 Business Context

RevoBank Indonesia aims to encourage existing customers to use its credit 
card products more frequently. This project focuses on preparing clean and 
reliable datasets that will later support customer segmentation and 
performance analysis.

---

## 🔍 What Was Done

- **Data type validation** — fixed incorrect types (e.g. `credit_limit`, 
  `amt_nonfraud_trx_L6M` converted from object to float)
- **Categorical standardization** — corrected inconsistent category values 
  using string formatting aligned to the data dictionary
- **Missing value treatment** — identified and handled nulls across 
  5,500+ card records and 2,000 user profiles
- **Business rule filtering** — excluded cards with missing or invalid 
  credit limits, as credit limit is essential for financial analysis
- **Duplicate removal** — ensured record uniqueness across both datasets

---

## 📊 Visualizations

| Chart | Description |
|---|---|
| `Bar char avg card brand.png` | Average metrics by card brand |
| `Bar chart DTI ratio by credit score category.png` | DTI ratio across credit score groups |
| `Line chart avg credit limit by age.png` | Credit limit trends by age |
| `Ple chart fraud.png` | Fraud transaction distribution |
| `boxplot DTI distribution.png` | DTI ratio spread & outliers |
| `Customer Segmentation/` | Segmentation result charts |

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data cleaning & preparation |
| Google Colab | Notebook environment |

---

## 📁 Files

| File | Description |
|---|---|
| `[PYTHON_OCT25]_FSDA_Dendy_Satrio.ipynb` | Full data cleaning notebook |
| `INT_card_data.csv` | Raw credit card dataset |
| `INT_user_data.csv` | Raw user dataset |
| `*.png` | Visualization charts |
