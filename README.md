# 📊 Healthcare Analytics (Excel Project)

This repository contains a **fictional healthcare dataset with 10,000 rows**.  
The dataset was created for practicing **Excel data analytics** and to showcase knowledge in:

- Excel formulas & functions (`SUMIFS`, `IF`, `XLOOKUP`, `TEXT`, `DATE`, etc.)
- Pivot tables & pivot charts
- Conditional formatting
- Data cleaning & transformation
- Lookup operations
- Dashboard creation for insights

The project is part of my preparation for the **Google Data Analytics Apprenticeship (March 2026)**.  
It demonstrates both **technical Excel skills** and the ability to structure a professional analytics project.

---

## 📂 Dataset Information

**File:** `data/healthcare_dataset.xlsx`  
**Rows:** ~10,000  
**Type:** Fully fictional (no real patient data used)  

### Key Columns
- `Patient_ID`
- `Age`
- `Gender`
- `Admission_Date`
- `Discharge_Date`
- `Department`
- `Doctor`
- `Diagnosis`
- `Treatment`
- `Length_of_Stay`
- `Bill_Amount`
- `Payment_Method`
- `Insurance_Provider`

This structure allows for practicing **time-based analysis, financial analysis, and patient trends**.

---

## ❓ 10 Essential Practice Questions

These are analytics-style questions to solve in Excel.  
Each question has a placeholder **solution area** (where I will add formulas, and pivot table steps).  

### Top 10 Patients by Treatment Cost (Highest Spenders)

Here is a preview of the Excel analysis:
![Top 10 Patients by Treatment Cost](docs/screenshots/top10_cost_spenders.png)


2. **Which 5 doctors generated the highest total billing?**  
   _Solution: (Pivot + sort + chart)_

3. **What is the trend of patient admissions by month in 2023?**  
   _Solution: (Pivot table grouped by month)_

4. **How many patients used insurance vs. self-pay?**  
   _Solution: (Pivot + pie chart)_

5. **Which diagnosis has the longest average length of stay?**  
   _Solution: (Pivot + calculated field)_

6. **Find patients admitted in January 2023 with bills > $5,000.**  
   _Solution: (`FILTER` or advanced filter)_

7. **What is the distribution of patients by age group (e.g., 0–18, 19–35, 36–60, 60+)?**  
   _Solution: (Helper column + Pivot chart)_

8. **Which insurance provider covers the highest total billing?**  
   _Solution: (Pivot table by Insurance Provider)_

9. **Use a lookup formula to return the department of a given patient ID.**  
   _Solution: (`XLOOKUP` or `VLOOKUP`)_

10. **Highlight bills above the department average using conditional formatting.**  
    _Solution: (Conditional formatting with formula rule)_

---

## 📊 Dashboard Ideas

I plan to build an **Excel dashboard** using slicers, pivot charts, and KPIs.  

Key features:
- **Admissions Overview**: Monthly admissions trend, top 5 diagnoses.  
- **Financial Analysis**: Department-wise revenue, top doctors by billing.  
- **Patient Demographics**: Gender split, age group distribution.  
- **Insurance Insights**: Insurance vs. self-pay analysis, top insurance providers.  
- **Length of Stay Analysis**: Average stay by department/diagnosis.  

Example layout:
- **Top row** → KPIs (Total Patients, Avg Bill, Avg Stay)  
- **Left side** → Slicers (Year, Department, Payment Method)  
- **Center** → Pivot charts (admissions trend, billing distribution)  
- **Right side** → Tables (top doctors, insurance breakdown)  

---

## 📸 Adding Images

I will add:
- **Screenshots of pivot tables & formulas** in the `images/` folder  
- **Final dashboard screenshot** to showcase my work  

Example:
```markdown
![Admissions Trend](images/admissions_trend.png)

## 🚀 Project Goal

This repository is not just a dataset — it is a portfolio project designed to:
1. Demonstrate advanced Excel skills.
2. Practice storytelling through dashboards.
