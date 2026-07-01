# sales-performance-dashboard-powerBI
# 📊 Executive Retail Sales & Performance Dashboard
An end-to-end data analytics portfolio project tracking performance across multinational retail stores using Excel, SQL, and Power BI. 

**Project Goal:** Standardise the data pipeline, automate processing via a centralised SQL database, and engineer a high-level interactive Power BI dashboard to deliver real-time, remote analytics for traveling executives.

---

## 🛠️ Data Pipeline & Architecture
The project follows a robust, real-world data analytics workflow:
1. **Extraction & Preparation (Excel):** Structured raw multi-country datasets and clean schemas to ensure uniform formats across global store operations.
2. **Data Integration & ETL (PostgreSQL):** Built a unified relational schema, managed variables, handled duplicate/null cleaning via advanced SQL queries, and consolidated tables via `UNION ALL`.
3. **Automated Cloud Backups:** Engineered a pipeline leveraging
for desktop storage synchronization to secure database states automatically.
4. **Data Modeling & Visualization (Power BI):** Imported clean data via a live PostgreSQL connection. Handled advanced date logic (extracting dynamic Month/Day sort indexing via Power Query) and established explicit business KPIs.

## 📊 Key Dashboard Insights & Impact
- **Dynamic Slicing Architecture:** Enabled executive filtering down to the Country, Store Location (City), Product Category, and Payment Method level.
- **Geospatial Sales Intelligence:** Plotted localized mapping using dynamic bubble scaling—revealing high-margin profiles across countries operations relative to higher discount, lower margin nodes in emerging regions.
- **Operational Trend Lines:** Visualized continuous monthly sales trends alongside localized daily revenue velocities, successfully identifying prime weekday transaction spikes to coordinate staff and supply demands.
