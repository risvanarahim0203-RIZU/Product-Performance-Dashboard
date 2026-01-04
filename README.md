# Multi-Market Sales Intelligence & Product Performance Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data_Modeling-0078D4?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-20232A?style=for-the-badge)

## 1. Project Title
**Enterprise Sales Intelligence & Global Product Performance Analytics**

## 2. Business Problem Statement
Organizations operating across multiple product categories and geographical regions often struggle with fragmented data, making it difficult to identify underperforming assets or capitalize on high-growth trends. Without a centralized "Single Source of Truth," leadership lacks the visibility required to optimize supply chains and marketing spend.

This analysis addresses the need for high-level executive visibility and granular operational detail. It is designed for **Sales Directors, Operations Managers, and Senior Financial Analysts** to monitor revenue health, profitability margins, and product lifecycle performance.

## 3. Objective of the Analysis
The primary goal of this dashboard is to transform raw transactional data into actionable commercial insights. Specifically, it aims to:
* 📈 **Evaluate** sales and profit performance against historical trends.
* 🔍 **Identify** high-value product categories and geographic hotspots.
* 📊 **Optimize** inventory and sales strategies by understanding the relationship between quantity sold and net profitability.

## 4. Dataset Overview
* **Data Source:** Multi-relational ERP export (Orders, Products, Companies, Geography, and Categories).
* **Time Period:** January 2021 – April 2025.
* **Key Entities:** * **Orders:** ~1,200 transactional records (Sales, Cost, Profit, Quantity).
    * **Products:** 50+ unique SKUs across 5 major categories (Electronics, Fashion, Furniture, Tools, Sporting).
    * **Geography:** 10 major US market hubs (New York, Seattle, Chicago, etc.).

## 5. Key KPIs
* **Total Sales** – Gross revenue generated from completed transactions.
* **Total Profit** – Net earnings after Cost of Goods Sold (COGS) and discounts.
* **Total Orders** – Volume of transactions, indicating market demand and operational load.
* **Total Quantity** – Physical volume of units moved, essential for supply chain planning.

## 6. Analysis Approach & Steps
1. **Data ETL (Power Query):** Cleaned and normalized disparate CSV tables; handled date formatting and established a dedicated `dimDate` table to support Fiscal Year (April–March) reporting.
2. **Data Modeling:** Developed a **Star Schema** with a central `Orders` fact table connected to dimension tables (`Product`, `City`, `Company`, `Category`) to ensure high-performance filtering.
3. **DAX Engineering:** Authored measures for Year-to-Date (YTD) totals, Fiscal Year comparisons, and dynamic ranking.
4. **UI/UX Design:** Implemented a high-contrast, professional interface using a "Top-Down" information hierarchy.
5. **Selection Logic:** Integrated a dynamic selection parameter allowing users to toggle the entire dashboard view between **Sales, Orders, and Returns**.

## 7. Dashboard Highlights
* **Executive Summary Tiles:** Provide immediate orientation on four core health metrics.
* **Sales/Profit by Product (Bar Chart):** Ranks the Top 10 products, allowing managers to identify "Hero SKUs" versus low-margin items.
* **Geographic Performance (Map):** Visualizes revenue density across city hubs to guide regional marketing efforts.
* **Trend Analysis (Area Chart):** Tracks performance over time to identify seasonal peaks and cyclical demand shifts.

## 8. Key Findings & Insights
* **Top Revenue Driver:** The **Camera (P001)** and **Projector (P022)** consistently lead in sales volume, indicating a strong market position in the Electronics category.
* **Regional Dominance:** **New York (C01)** and **Seattle (C02)** represent the highest sales density, suggesting mature markets with high customer lifetime value.
* **Profitability Correlation:** High sales volume does not always equate to top-tier profit; certain "Tools" items show higher margins despite lower unit volume.
* **Temporal Trends:** Significant growth is visible in the 2023–2024 period, with clear month-over-month fluctuations suggesting sensitivity to quarterly procurement cycles.

## 9. Business Impact & Recommendations
* **Inventory Optimization:** Increase safety stock for Top 5 SKUs in East Coast hubs to prevent stockouts.
* **Strategic Discounting:** Analyze high-volume/low-profit items to determine if aggressive discounting is eroding the bottom line.
* **Market Expansion:** Use the success in New York as a blueprint for underperforming regions like Jacksonville or San Jose.

## 10. Tools & Technologies Used
* **Power BI Desktop:** End-to-end development.
* **DAX:** Complex measures and time-intelligence logic.
* **Power Query (M):** Data ETL and schema normalization.
* **Data Modeling:** Star Schema architecture.

## 11. Project Outcome
This project demonstrates the ability to take raw, multi-table business data and create a sophisticated, interactive BI solution. It showcases expertise in **Data Modeling, DAX, and Executive-Level Data Storytelling**, providing a tool that turns historical data into forward-looking strategy.

## 12. Author & Portfolio Note
This project is a core component of my **Professional Data Analytics Portfolio**. It reflects my commitment to delivering high-impact, enterprise-grade business intelligence solutions that drive data-informed decision-making.

---
📫 **Connect with me:** [LinkedIn Profile Link] | [Your Portfolio Website]
