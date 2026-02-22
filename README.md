# E-Commerce Sales Analytics & Customer Behavior Analysis

## 📌 Project Objective
Performed end-to-end data analysis on a large-scale online retail dataset to evaluate revenue trends, customer purchasing behavior, product performance, and business risk concentration.

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib)
- Power BI
- VS Code
- Excel

---

## 🧹 Data Cleaning & Preprocessing
- Removed missing CustomerID and Description values
- Eliminated invalid transactions (Quantity ≤ 0, UnitPrice ≤ 0)
- Created a clean working dataset for reliable analysis

---

## ⚙️ Feature Engineering
- Created Revenue column (Quantity × UnitPrice)
- Extracted Year, Month, Day, Hour from InvoiceDate
- Generated YearMonth column for time-series analysis

---

## 📊 Exploratory Data Analysis (EDA)

### Revenue Analysis
- Calculated total business revenue
- Identified top 10 revenue-generating countries
- Analyzed top-performing products

### Time-Series Analysis
- Evaluated monthly revenue trends
- Identified seasonal sales patterns
- Visualized revenue growth over time

### Customer Analysis
- Identified unique customers
- Analyzed repeat vs one-time customers
- Calculated revenue per customer
- Identified top 10 high-value customers

### Business Risk Assessment
- Measured revenue concentration among top customers
- Evaluated dependency risk using revenue percentage analysis

---

## 📈 Key Insights
- Revenue shows overall upward trend with seasonal variations
- Small percentage of products contribute major revenue (Pareto pattern)
- Repeat customers contribute significant revenue share
- Revenue concentration among top customers indicates potential business risk

---

## 📁 Final Output
- Cleaned dataset exported for dashboard creation
- Interactive Power BI dashboard built using processed data

## 📊 Dashboard Preview

[E-Commerce Dashboard](plots/dashboard_overview.png)


