# 📊 Excel-Business-Intelligence-AtliQ-Hardwares-Finance-Performance-Analytics-Report

An end-to-end **Finance Analytics portfolio project** built using **Advanced Excel**, **Power Query**, **Power Pivot**, and **DAX**, focused on analyzing **Profit & Loss (P&L)** and **Gross Margin (GM%)** performance across **months, quarters, fiscal years, and markets**.

This project demonstrates strong fundamentals in **financial analysis**, **data modeling**, and **Excel-based BI**, following a structured **ETL (Extract, Transform, Load)** approach.

---

## 🚀 Finance Analytics Report
### 📁 P&L Statement by Fiscal Year - (https://github.com/prajwal-555/-Excel-Business-Intelligence-AtliQ-Hardwares-Finance-Performance-Analytics-Report/blob/main/P%26L%20Statement%20by%20Fiscal%20Year.pdf)

### 📁 P&L Statement by Month - https://github.com/prajwal-555/Excel-Business-Intelligence-AtliQ-Hardwares-Finance-Performance-Analytics-Report/blob/main/P%26L%20Statement%20by%20Month.pdf

### 📁 P&L Statement by Market - https://github.com/prajwal-555/Excel-Business-Intelligence-AtliQ-Hardwares-Finance-Performance-Analytics-Report/blob/main/P%26L%20Statement%20by%20Market.pdf

### 📁 Gross Margin% by Quarters - https://github.com/prajwal-555/Excel-Business-Intelligence-AtliQ-Hardwares-Finance-Performance-Analytics-Report/blob/main/Gross%20Margin%25%20by%20Quarters.pdf
---

## 📌 Table of Contents
- 📖 Project Overview  
- 🎯 Business Objective  
- 🛠 Tools & Technologies  
- 🔄 ETL Methodology  
- 🧱 Data Model  
- 📐 Key Metrics  
- 📈 Analysis & Insights  
- 📊 Excel Dashboard Overview  
- 📂 Repository Structure  
- 💡 Technical Skills
- 🚀 Soft Skills 

---

## 📖 Project Overview
The objective of this project is to transform raw financial reports into **meaningful business insights** using Excel’s modern analytics stack.

The analysis covers:
- ✅ **P&L performance** by month, quarter, fiscal year, and market  
- ✅ **Gross Margin % trends** across regions and sub-zones  
- ✅ **Year-over-Year (YoY) growth** in Net Sales and Gross Margin  
- ✅ Identification of **high-performing and low-performing markets**

All analysis is performed entirely in **Microsoft Excel**, simulating a real-world finance reporting workflow.

---

## 🎯 Business Objective
This project aims to answer key business questions such as:
- 📈 How has **revenue and profitability evolved over time**?
- 🌍 Which **markets drive the highest sales and margins**?
- ⚠️ Where are margins **expanding or compressing**, and why?
- 🧭 How do **quarterly GM% trends differ by sub-zone**?

The insights generated can support **finance teams, leadership reviews, and strategic decision-making**.

---

## 🛠 Tools & Technologies
- 🧮 **Microsoft Excel (Advanced)**
- 🔄 **Power Query** – Data extraction, transformation, and cleaning
- 🧱 **Power Pivot** – Data modeling and relationships
- 📐 **DAX (Data Analysis Expressions)** – Calculated measures & KPIs
- 📊 Pivot Tables & Pivot Charts
- 📉 Excel Dashboards

---

## 🔄 ETL Methodology (Extract, Transform, Load)

### 📥 1. Extract
- Imported multiple **P&L and Gross Margin reports** into Excel
- Source data provided in report-style formats (monthly, quarterly, yearly, market-wise)

### 🔧 2. Transform
Performed extensive data cleaning and transformation using **Power Query**:
- 🧹 Removed unnecessary formatting and blank rows
- 🏷 Standardized column names and data types
- 🔄 Unpivoted wide tables into analysis-ready formats
- 🗓 Created date hierarchies (Month → Quarter → Fiscal Year)
- ✅ Ensured consistent market and region naming

### 📤 3. Load
- Loaded cleaned data into the **Excel Data Model**
- 🧩 Built optimized fact and dimension tables
- 🔗 Created relationships using **Power Pivot**

---

## 🧱 Data Model
The Excel Data Model follows a **star-schema-inspired design**:
- ⭐ **Fact Tables**:
  - fact_Sales_monthly
- 📂 **Dimension Tables**:
  - dim_Customer
  - dim_market
  - dim_product
  - dim_date

 <img width="1013" height="512" alt="image" src="https://github.com/user-attachments/assets/1b745644-3e04-4b1f-9928-db2accd804ef" />

This structure enables fast slicing, filtering, and scalable analysis using Pivot Tables and DAX.

---

## 📐 Key Metrics (DAX)
Key measures created using DAX include:
- 💰 Net Sales = SUM(fact_sales_monthly[net_sales_amount])
- 💰 Net Sales 2019 = CALCULATE([Net Sales],dim_date[FY]="2019")
- 💰 Net Sales 2019 = CALCULATE([Net Sales],dim_date[FY]="2020")
- 💰 Net Sales 2019 = CALCULATE([Net Sales],dim_date[FY]="2021")
- 🧾 COGS = SUM(fact_sales_monthly[total_cogs])
- 📈 Gross Margin = [Net Sales]-[COGS]
- 📊 Gross Margin % = DIVIDE([Gross Margin],[Net Sales],0)
- 📅 21 vs 20 % = DIVIDE([Net Sales 21],[Net Sales 20],0)


All metrics dynamically respond to filters across time periods and markets.

---

## 📈 Analysis & Insights (Examples)

### 💹 Revenue Growth
- Strong acceleration in **Net Sales from FY2019 → FY2021**
- FY2021 shows exponential growth compared to previous years

### 📉 Margin Trends
- Overall **Gross Margin % has slightly declined** despite revenue growth
- Indicates pricing pressure, cost increases, or product mix changes

### 🌍 Market Performance
- Certain markets contribute significantly to revenue but operate at **lower margins**
- Smaller markets show **higher GM%**, indicating premium or efficient segments

### 🗓 Quarterly GM% Analysis
- GM% varies by **sub-zone and quarter**
- Some regions show stable margins, while others display volatility

---

## 📊 Excel Dashboard Overview
The Excel dashboard includes:
- 📌 **Executive Summary KPIs**
- 📆 **Monthly & Quarterly Trend Analysis**
- 🌍 **Market-wise Performance Comparison**
- 🔥 **Gross Margin % DataBars**
- 🎛 **Interactive filters** for Year, Quarter, Market, and Region

> The dashboard is fully dynamic and built using Pivot Charts connected to the Data Model.

## 🎯 Technical & Soft Skills:
- [x]	Proficiency in ETL methodology (Extract, Transform, Load).
- [x]	Skills to generate a date table using Power Query.
- [x]	Ability to derive fiscal months and quarters.
- [x]	Establishing data model relationships with Power Pivot.
- [x]	Proficiency in incorporating supplementary data into an existing data model.
- [x]	Utilizing DAX to create calculated columns.

## 🎯 Soft Skills:
- [x]	Refined understanding of Sales & Finance Reports
- [x]	Designing user-centric reports with empathy in mind.
- [x]	Optimization of report generation through meticulous fine-tuning.
- [x]	Developing a systematic approach to devising a report building plan.
