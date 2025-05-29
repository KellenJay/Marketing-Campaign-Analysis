# Marketing Campaign Performance Analysis

This project analyzes marketing campaign performance data to identify underperforming ads, optimize channel strategy, and generate actionable business insights using a full-stack data analytics approach.

 **Tools Used:**  
- **SQL (T-SQL):** End-to-end data modeling, EDA, KPI development, reporting logic, and trend analysis.  
- **Microsoft Excel:** Initial data cleaning, pivot reporting, KPI prototyping, and exploratory comparisons.

---

## Data Architecture

This project features a **modular data warehouse** built using the **Medallion Architecture** (Bronze → Silver → Gold), including:

- **Bronze Layer:** Raw ingestion tables from marketing sources.
- **Silver Layer:** Cleaned and enriched campaign data (`silver.marketing_campaign`).
- **Gold Layer:** Final analytical views and reports for BI tools:
  - `gold.fact_campaign` (fact view with calculated KPIs)
  - `gold.report_campaigns` (executive performance report)

Developed using:
- **Stored Procedures** for repeatable transformation logic.
- **Views** for analytical presentation.
- **Surrogate Keys** via `ROW_NUMBER()` for fact table identity.

---

## Project Objectives

- Explore marketing performance across campaigns, cities, devices, and channels.
- Build reusable KPIs: **CTR, CPC, CPM, ROAS, RPC, ROI, Conversion Rate, Engagement Rate**.
- Perform segmentation analysis, profitability flagging, and performance benchmarking.
- Conduct **MoM growth tracking** and build **data-rich reports** for strategic decision-making.

---

## Key SQL EDA Topics Covered

-  **Dimension Exploration:** Unique channel, ad, device, and city combinations.
-  **Date Range Analysis:** Temporal boundaries and campaign lifespan.
-  **Magnitude Analysis:** Totals for clicks, impressions, conversions, and revenue.
-  **Ranking:** Best and worst performing ads, products, and locations.
-  **Change Over Time:** Monthly revenue growth and customer engagement trends.
-  **Part-to-Whole Analysis:** Channel contribution to overall campaign ROI.
-  **Segmentation Logic:** Categorizing campaigns and cities for optimization.
-  **Performance Flagging:** Identifying loss-making campaigns.

---

## Project Structure

- `sql_scripts/`: All EDA queries, KPI calculations, and reporting logic.
- `warehouse_views/`: DDL for `gold.fact_campaign` and `gold.report_campaigns`.
- `stored_procedures/`: Modular procedure logic for ETL tasks.
- `excel_reports/`: Early-stage exploratory analysis and KPI dashboards.

---

## Outcome

This project demonstrates how to structure a **full-stack analytics solution**:
- From raw marketing data to a clean data warehouse,
- From KPI modeling to SQL-based reporting,
- From Excel exploration to BI dashboard readiness.

It highlights **best practices in SQL development, data warehousing, and marketing performance analysis**.



