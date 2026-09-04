# Customer Shopping Behavior Analysis

A complete data analytics project that takes a raw retail dataset from cleaning to business insights — combining **Python**, **SQL**, **Power BI**, and a stakeholder-ready presentation.

## 📌 Overview
This project analyzes customer shopping behavior to help a retail company understand what drives purchasing decisions, discount usage, and customer loyalty. It follows a real-world analytics workflow: load → clean → analyze → visualize → report → present.

## 🗂️ Dataset
- **Source:** Customer shopping behavior dataset (CSV)
- **Size:** 3,900 records × 18 attributes
- **Fields:** demographics (age, gender, location), product details (category, item, color, size), purchase amount, review rating, subscription status, discount/promo usage, shipping type, payment method, and purchase frequency

## 🛠️ Tools
| Stage | Tool |
|---|---|
| Data cleaning & EDA | Python (pandas) |
| Database | PostgreSQL / SQL Server |
| Business analysis | SQL |
| Visualization | Power BI |
| Report | Word / PDF |
| Presentation | PPT (built with Gamma) |

## 🔄 Steps
1. **Load Dataset** — Imported the raw CSV into Python for inspection
2. **Data Cleaning (Python)** — Handled missing values, standardized column names, fixed data types, engineered new features (e.g., age group, purchase frequency)
3. **Exploratory Data Analysis (Python)** — Profiled distributions, correlations, and category-level patterns
4. **SQL Analysis** — Loaded cleaned data into PostgreSQL/SQL Server and ran structured queries to answer key business questions (revenue drivers, discount behavior, customer segmentation, top products)
5. **Power BI Dashboard** — Built an interactive dashboard with KPI cards, charts, and slicers for self-service exploration
6. **Report** — Documented methodology, findings, and business recommendations
7. **Presentation** — Summarized insights into a stakeholder-facing PPT using Gamma

## 📊 Results
- Identified key revenue drivers across gender, category, and age group
- Found discounting is used broadly across spend levels, not just by price-sensitive customers
- Segmented customers into New, Returning, and Loyal groups to guide retention strategy
- Delivered an interactive dashboard and a set of actionable business recommendations

## ▶️ How to Run
1. Clone this repository
2. Open `customer_shopping_behavior.ipynb` in Jupyter/VS Code and run all cells to clean the data
3. Load the cleaned data into PostgreSQL/SQL Server and run the queries in `customer_behavior.sql`
4. Open `customer_behavior_dashboard.pbix` in Power BI Desktop to explore the dashboard
5. Refer to the project report (PDF/Word) for full findings and recommendations

## 👤 Author
**Ansh Rawal** — MBA (International Business), MIT College of Management, Pune
