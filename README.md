# E-Commerce Sales Performance Dashboard

## 📊 Project Overview
This interactive Power BI dashboard provides a comprehensive, data-driven analysis of e-commerce sales performance. It transforms raw business data into actionable business intelligence, allowing stakeholders to track profitability, optimize supply chains, and understand consumer behavior across various regions.

### 🔗 Key Features
*   Core Sales Tracking: Live monitoring of total profit, total quantity sold, and average order value (AOV).
*   Geographic Deep-Dive: Dynamic mapping and filtering by State and City (e.g., Delhi, Mumbai, Pune, Indore) to uncover localized market trends.
*   Interactive UX: Integrated dropdown slicers and sync-filters for seamless, responsive data exploration.
*   Advanced Data Storytelling: A cohesive layout utilizing KPI cards, trend lines, and breakdown bar charts tailored for executive decision-making.

---

## 🛠️ Tech Stack & Architecture
*   Power BI Desktop: Core tool used for semantic data modeling, report layout design, and report publishing.
*   Power Query (M): Utilized for the Extract, Transform, Load (ETL) pipeline to clean, shape, and merge raw data structures.
*   DAX (Data Analysis Expressions): Written to build optimized calculated measures and analytical columns for accurate business metrics.

### 🗃️ Dataset Architecture
The semantic data model is built on two primary relational datasets:
1.  Orders.csv – Contains transactional data including order dates, customer identifiers, and shipping logistics.
2.  Details.csv – Contains granular line-item data including product categories, sub-categories, quantities, pricing, and profit margins.

---

## 📈 Dashboard Preview


![E-Commerce Sales Dashboard Screenshot](https://github.com/user-attachments/assets/3b90d958-3b4f-4ed4-a218-6388da6dbb95)

---

## ⚙️ Data Pipeline & Transformation Highlights
Before building the visuals, the data underwent rigorous cleaning inside Power Query:
*   Data Type Validation: Ensured all currency, date, and quantity fields were explicitly defined to prevent query degradation.
*   Relational Modeling: Established clean star/snowflake schema relationships between the Orders.csv and Details.csv tables.
*   Calculated Measures: Developed DAX measures to calculate performance KPIs dynamically based on user-selected slice parameters.

---

