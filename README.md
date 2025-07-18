# Business Insights 360

## 📌 Project Overview

AtliQ Hardware is a rapidly growing company that has decided to adopt data analytics to gain a competitive advantage. This Power BI project enables stakeholders to derive key insights across **Finance**, **Sales**, **Marketing**, and **Supply Chain** to drive data-informed decisions.

This end-to-end dashboard was built by following the [Codebasics Power BI Course](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project), where concepts were implemented step-by-step from raw data to insights.

🎯 **Main Goal**: Help AtliQ Hardware move away from intuition-based decisions and enable data-driven strategies for growth and optimization.

---

## 🛠️ Tech Stack

- Power BI Desktop  
- SQL (MySQL)  
- Excel  
- DAX Language  
- DAX Studio (for optimization)  
- Power Query (M Language)  
- Git & GitHub LFS (for large file handling)

---

## 🗃️ Importing Data into Power BI

- The source database for this project is **MySQL**.
- Data was imported into Power BI Desktop using MySQL Database connector.
- Access credentials were provided to establish the connection and load the required tables.

---

## 🧩 Data Model

- Data modeling is the **foundation** of a successful Power BI report.  
- A poor data model can drastically affect report **performance and accuracy**.
- The project follows **Snowflake Schema** modeling.
- Relationships were defined between fact and dimension tables using proper keys.
- Data model optimization techniques were followed to ensure scalability and maintainability.

> 🔗 Refer to this [blog post on data modeling best practices](https://addendanalytics.com/blog/data-modelling-best-practices/) for more guidance.

---

## 📂 Dataset Details

- **Source**: MySQL database (imported directly into Power BI)
- **Data Structure**: Snowflake schema
- **Types of Tables**:
  - **Dimension tables**: `dim_customer`, `dim_market`, `dim_product`
  - **Fact tables**: `fact_sales_monthly`, `fact_forecast_monthly`, `freight_cost`, `gross_price`, `manufacturing_cost`, `pre_invoice_deductions`, `post_invoice_deductions`

---

## 🧠 Business Concepts Covered

- Gross Sales vs Net Sales  
- Pre-Invoice & Post-Invoice Deductions  
- Gross Margin & Net Profit  
- Year to Date (YTD) & Year to Go (YTG)  
- COGS (Cost of Goods Sold)  
- Sales Channels: Direct, Retailer, Distributor

---

## 📈 Power BI Features Implemented

- Data modeling (Snowflake schema)
- KPI cards and dynamic titles
- Conditional formatting with icons & colors
- Navigation using bookmarks and buttons
- Forecasting vs actual comparisons
- DAX measures and calculated columns
- Tooltips and drill-down interactions
- Dashboard-level filters and slicers
- Performance optimization using DAX Studio

---

## 🧭 Home View

- **Navigation hub** for users to access each business view  
- Contains buttons with bookmarks to Finance, Sales, Marketing, and Supply Chain views  
- **Last Refreshed Date** and **data currency info** also displayed  
- Values are shown in **Millions ($)**  

---

## 💰 Finance View

- **KPI Cards**: Net Sales, Gross Margin %, Net Profit % (compared to LY or targets)  
- **Profit & Loss Summary**: Revenue, expenses, deductions  
- **Top & Bottom Customers**: Based on Net Sales and Profitability  
- Insight into financial health of the organization over time

---

## 📊 Sales View

- **Customer & Product Performance**: Based on Net Sales and Gross Margin %  
- **Performance Matrix**: Scatter plot to show high-value customers (Net Sales vs GM %)  
- **Key Metrics by Product Category**: Net Sales, Deductions, COGS, Gross Margin  
- Helps in identifying high-performing segments

---

## 📣 Marketing View

- **Marketing KPIs**: Net Profit %, Product-wise performance  
- **Customer Region Analysis**: Based on Net Sales and Profitability  
- **Unit Economics**: Donut charts for margin breakdown, Waterfall for operational profit  
- **Performance Matrix**: Filterable by Net Profit % or GM %  

---

## 🚚 Supply Chain View

- **KPI Cards**: Forecast Accuracy, Net Error, Absolute Error  
- **Forecast vs Actual Trends**: Monthly comparisons using combo charts  
- **Product-wise Error Analysis**: Understand deviation across categories  
- Helps optimize inventory and reduce cost of storage

---

## 📁 Report File

🔽 Download the Power BI file: [360.pbix](https://github.com/Naveen-S6/Business_Insights_360/blob/main/Report/360.pbix)

---

## ✅ Project Outcome

This Power BI solution delivers a unified, data-rich environment for stakeholders to evaluate business performance in real time. With interactive visuals and insightful breakdowns, it enables AtliQ Hardware to make smarter decisions, reduce risks, and drive profitability.

---

## 💡 Skills Demonstrated

### Technical Skills
- ETL using Power Query  
- DAX-based calculations and optimizations  
- MySQL data integration  
- Report performance tuning (DAX Studio)  
- Advanced Power BI visualizations & bookmarks  

### Soft Skills
- Business acumen across Finance, Sales, Marketing, and Supply Chain  
- Stakeholder-centric dashboard design  
- Data storytelling and insight delivery  
- Requirement gathering and implementation  
