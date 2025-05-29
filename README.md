# 📊 Marketing Campaign Performance Analysis

This project analyzes marketing campaign performance data to identify underperforming ads, optimize channel strategy, and derive actionable business insights.

🔧 **Tools Used:**  
- **Microsoft Excel:** Initial data exploration, cleaning, pivot reporting, and KPI prototyping.  
- **SQL (T-SQL):** End-to-end EDA (Exploratory Data Analysis), KPI calculations, segmentation logic, time-based trend analysis, and final view/report generation using structured queries.

---

## 🧠 Project Objectives

- Explore marketing campaign data across multiple dimensions (channel, city, device, etc.)
- Calculate business KPIs such as **CTR, CPC, ROAS, ROI, Conversion Rate, RPC**, and more.
- Segment performance by customer behavior and geographic targeting.
- Build a **Gold Layer fact view and report** using SQL for dashboard integration.
- Compare yearly channel revenue trends using **YoY analysis** and **window functions**.

---

## 🗂️ Key SQL EDA Topics Covered

- ✅ **Dimensions Exploration:** Extracting unique channel, city, and ad variants.
- 📅 **Date Range Analysis:** Identifying historical span and seasonal patterns.
- 📏 **Magnitude & Aggregates:** Calculating total clicks, revenue, and ad spend.
- 🏆 **Ranking:** Finding top-performing ads and cities based on ROI.
- 📈 **Change Over Time:** Monthly revenue trends using `DATETRUNC()` and `FORMAT()`.
- 🔁 **Running Totals & Moving Averages:** Trend tracking using `OVER()` window functions.
- 📊 **Part-to-Whole Analysis:** Channel contribution to total revenue.
- 🔍 **Segmentation:** Customer and product-based segmentation for strategic insights.
- 📉 **Performance Flags:** Identifying loss-making campaigns for corrective action.

---

## 🧾 Project Structure

- `sql_scripts/`: All SQL EDA, metrics calculation, and reporting scripts.
- `excel_reports/`: Pivot tables and performance dashboards.
- `gold_views/`: Final SQL scripts for `gold.fact_campaign` and `gold.report_campaigns`.

---

## 🔗 Project Portfolio

- 📘 [Project Summary & Dashboard](https://www.notion.so/Marketing-Campaign-Analysis-19968abd1c54802daca2cfeb3b5a4106)
- 📎 [Detailed SQL Report Walkthrough](https://www.notion.so/Detailed-Report-For-More-Information-19968abd1c5481ce9282d4c1925795a4)

---

## 📌 Outcome

This project demonstrates the power of **structured data exploration using SQL** alongside **interactive visual analysis in Excel**—enabling stakeholders to make smarter decisions about **ad strategy, audience targeting, and budget optimization**.


