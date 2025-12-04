# Bike Buyer Analysis Dashboard 🚴‍♂️📊

This project analyzes customer demographics and purchasing behavior to understand which segments are more likely to buy a bike. The analysis includes data cleaning, feature engineering, pivot analysis, Excel formulas, and a dynamic dashboard.

---

## 🎯 Objective

To help a bike company identify:
- Who buys more bikes?
- Which regions show higher purchase conversion?
- Which customer segments should be targeted for marketing?

This enables **data-driven sales and marketing decisions**.

---

## 📁 Project Structure
```bash
bike-buyer-analysis/
│
├─ data/
│ ├─ bike_sales_raw.xlsx
│ └─ bike_sales_cleaned.xlsx
│
├─ images/
│ ├─ dashboard.png
│ ├─ eda_pivots.png
│ └─ formulas.png
│
└─ README.md
```


---

## 🧹 Data Cleaning & Feature Engineering

Performed in Excel using:
- Removal of duplicates
- Standardization of categorical values
- Formatting numeric columns (Income)
- Feature creation using formulas:
  - `Age Bracket` (Adolescent / Middle Age / Old)
  - `Income Bucket` (Low / Medium / High)
  - `Buyer Flag` (1 or 0)
  - `Avg Region Income` (VLOOKUP mapping)

✔ Total rows: 1000  
✔ Columns cleaned: 17  
✔ 4 new useful features created

---

## 🔍 Exploratory Data Analysis (Pivot Tables)

Key analyses:
- Buyer percentage by Region
- Buyer distribution by Gender
- Age category buyer trends
- Income level insights
- Occupation & education influences

📌 **Screenshots available in `images/` folder**

---

## 📊 Dashboard Highlights

An interactive Excel dashboard built using:
- Pivot Charts
- Slicers for filtering (Gender, Marital Status, Region)
- KPI cards for quick insights

### ✨ Key Business Insights
- **Middle Age** group buys the most bikes (**79%**).
- **North America** has the highest buyer conversion (**45%+**).
- **Medium & High income** groups are top customer segments.
- **Males** buy slightly more bikes than females (**50.3% vs 49.6%**).

➡️ These findings help target marketing budget efficiently.

---

## 🧠 Excel Functions Used

| Category | Functions |
|---------|-----------|
| Aggregation | `COUNTIFS`, `SUMIFS` |
| Conditional | `IF`, `IFS` |
| Lookup | `VLOOKUP` |
| Date | `DATE`, `YEAR`, `MONTH`, `DAY` |
| Dashboard Tools | Pivot Tables, Slicers, Charts |

📌 Formula examples documented in `Formula Analysis` sheet (with explanation)

---

## 🛠 Tools & Skills Demonstrated

| Skill | Level |
|------|------|
| Excel Data Cleaning | ⭐⭐⭐⭐✰ |
| Pivot Tables & Charts | ⭐⭐⭐⭐⭐ |
| Feature Engineering | ⭐⭐⭐⭐✰ |
| Dashboards & KPIs | ⭐⭐⭐⭐✰ |
| Business Insight Storytelling | ⭐⭐⭐⭐⭐ |

---

## 🚀 Future Enhancements

- Publish dashboard online (Power BI version)
- Add churn and CLV analysis
- Automate insights using Python (Pandas)

---

## 🤝 Contact

If you're looking for help with **data cleaning, dashboards, and business analytics**, I’d love to collaborate!

📩 Email: *axaymathukiya27@gmail.com*  
🔗 LinkedIn: *https://www.linkedin.com/in/axay-mathukiya-a6989b308*  

---

### ⭐ If you like this project, please star the repo!

