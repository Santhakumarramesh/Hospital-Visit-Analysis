# 🏥 Hospital Visit Analysis

This project analyzes hospital visit data using Python and SQLite to extract valuable insights related to patients, doctors, diagnoses, and revenue trends.

## 📂 Project Overview

- **Objective**: Normalize hospital visit data, store it in a relational database, and perform analytical queries to derive business insights.
- **Tools Used**:  
  - `pandas` for data manipulation  
  - `sqlite3` for database operations  
  - `matplotlib` for visualization  

## 🗃️ Dataset

The dataset includes columns such as:
- Date of Admit / Discharge
- Doctor and Department
- Hospital Branch
- Patient ID and Name
- Revenue per Visit

> 📁 Sample File Used: `Hospital_Visits.csv`

## ⚙️ Process Flow

1. **Data Cleaning & Preparation**:  
   Extract unique tables for Patients, Doctors, and Diagnoses.

2. **Database Normalization**:  
   Normalize into 3rd Normal Form and store in SQLite tables.

3. **SQL Queries for Insights**:
   - Revenue by Department
   - Average Fee by Diagnosis
   - Most Frequent Patients
   - Most Active Doctors
   - Monthly Revenue Trend

4. **Visualizations**:  
   Generate bar and line plots for business-friendly summaries.

## 📊 Visual Output Examples

- Total Revenue by Department  
- Top 10 Diagnoses by Average Fee  
- Monthly Revenue Trend  
- Most Frequent Patients  
- Most Active Doctors

## 📁 Files

| File | Description |
|------|-------------|
| `Hospital_Visit_Analysis.ipynb` | Jupyter notebook with full code & plots |
| `Hospital_Visits.csv` | Sample input dataset |
| `hospital_visits_normalized.db` | Output SQLite database |
| `README.md` | This file |

## 🚀 How to Run

1. Clone this repository
2. Make sure `Hospital_Visits.csv` is in the same folder
3. Run `Hospital_Visit_Analysis.ipynb` in Jupyter or VS Code

---

✅ Feel free to extend this analysis by joining with external health datasets or adding a dashboard using Streamlit or Dash.

