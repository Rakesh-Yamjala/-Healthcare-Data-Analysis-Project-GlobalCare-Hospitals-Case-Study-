# 🏥 Healthcare Data Analysis Project — GlobalCare Hospitals (Case Study)

## 📌 Project Overview

This project simulates a real-world healthcare case study where I worked as a **Data Analyst** for a fictional hospital chain, **GlobalCare Hospitals**. The objective was to create a large-scale healthcare dataset and extract meaningful insights to support cost optimization, risk profiling, and operational reporting using **Python (Pandas & NumPy)**.

---

## 📊 Dataset Details

- ✅ **Type**: Synthetic / Dummy data
- ✅ **Size**: 100,000+ patient records
- ✅ **Columns**:
  - `Patient_ID` – Unique patient identifier  
  - `Name` – Patient name (synthetic)  
  - `Age` – Patient age  
  - `Gender` – Male / Female / Other  
  - `Country` – Country of treatment (USA, India, UK, etc.)  
  - `Disease` – Disease diagnosed (Diabetes, Cancer, COVID-19, etc.)  
  - `Admission_Date` – Date of hospital admission  
  - `Cost_USD` – Cost of treatment in USD

---

## 🛠️ Data Cleaning

Before analysis, I ensured high-quality data by:
- ✅ Removing duplicate patient records
- ✅ Handling missing or negative cost values
- ✅ Converting date columns to datetime format
- ✅ Ensuring consistent formatting and column types

---

## 📚 Case Study – Business Requirements

I extracted insights from the dataset based on **10 real-world client questions**, framed as business problems. Here's what I worked on:

| # | Business Requirement | Analysis Goal |
|---|----------------------|----------------|
| 1 | Top 3 countries with most patients in the last 1 year | Geographic demand trends |
| 2 | Average treatment cost per disease across countries | Disease-wise cost comparison |
| 3 | Count of elderly patients (Age > 60) per disease | Age-risk segmentation |
| 4 | Monthly cost trend for the past 2 years | Time-series financial trend |
| 5 | Top 5 most expensive treatment cases | Outlier/fraud detection |
| 6 | Cost difference by gender for each disease | Demographic analysis |
| 7 | Assign High/Low risk score based on age + disease | Risk profiling |
| 8 | Top 3 costliest diseases per country | Geographic cost drivers |
| 9 | Standard deviation of treatment cost by disease | Billing consistency check |
| 10 | Identify high-cost outliers (z-score > 3) | Anomaly detection |

---

## 🧠 Skills & Tools Used

- **Python**
- **Pandas** – Grouping, filtering, aggregations, pivoting
- **NumPy** – Vectorized operations, z-score detection, masking

---

---

## 🚀 How to Use

1. Clone the repository:
```bash
git clone https://github.com/Rakesh-Yamjala/healthcare-analysis.git


