# 🏥 Hospital Visits & Revenue Analysis

This project analyzes hospital visit data to extract meaningful insights, such as revenue trends, patient visit frequency, and doctor activity. The goal is to simulate how hospitals can use data analytics to improve resource allocation, understand patient behavior, and monitor departmental performance.

---

## 📁 Dataset

**Source:** Public sample dataset (uploaded manually)

**Filename:** `Hospital_Visits_Revenue.csv`

**Key Features:**
- `Date of Admit`, `Date of Discharge`
- `Doctor`, `Department`, `Hospital Branch`
- `Patient ID`, `Patient Name`
- `Revenue`, `Patient Risk Profile`, etc.

---

## 🔍 Project Workflow

1. **Load and preprocess CSV**
2. **Normalize data** into separate dataframes:
   - `Patients`
   - `Doctors`
   - `Diagnoses`
3. **Merge into a unified format** for analysis
4. **Run SQL-like queries using SQLite**
5. **Generate visualizations** for insights

---

## 📊 Key Insights

1. **Total Revenue by Department**
2. **Average Fee by Diagnosis**
3. **Most Frequent Patients**
4. **Most Active Doctors**
5. **Monthly Revenue Trends**

Each insight is visualized using clear and readable bar/line plots with labeled axes and rotated ticks for clarity.

---

## 🛠 Tools & Libraries

- Python 3.x
- `pandas` for data manipulation
- `sqlite3` for in-memory SQL operations
- `matplotlib` for data visualization

---

## 🧠 How to Use

1. Clone the repository
2. Make sure `Hospital_Visits_Revenue.csv` is in the same folder
3. Open `Hospital_Visit_Analysis.ipynb` in Jupyter Notebook or VSCode
4. Run all cells to:
   - Normalize the data
   - Generate insights
   - View visualizations

---

## ✅ Output Preview

> 📈 Visualizations included:
- Revenue bar charts
- Diagnosis cost trends
- Monthly line charts

---

## 📂 Repo Structure

├── Hospital_Visit_Analysis.ipynb
├── Hospital_Visits_Revenue.csv
└── README.md

---

## 💡 Author

**Santhakumar Ramesh**  
MPS in Data Science and Applications  
University at Buffalo  
[GitHub](https://github.com/Santhakumarramesh)

---

