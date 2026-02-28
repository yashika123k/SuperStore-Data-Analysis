# 📊 Superstore Sales Analysis – Excel Power BI (Data Model + Power Pivot)

## 🔎 Project Overview

This project presents an end-to-end Business Intelligence solution built using **Excel Power Query, Power Pivot, and Data Modeling techniques**.

The objective is to analyze sales performance, profitability, regional trends, operational efficiency, and seasonality using a structured **Star Schema Data Model**.

The solution demonstrates both technical modeling skills and business insight generation.

---

## 🏗 Data Architecture

The project follows a **Star Schema** design:

### 🟢 Fact Table

**Fact_Sales**
- Sales  
- Profit  
- Profit Margin  
- Quantity  
- Discount  
- Days Taken to Deliver  
- Order Date  
- Ship Date  
- Foreign Keys (Customer, Product, Geography, Ship Mode)

### 🔵 Dimension Tables

- Dim_Customer  
- Dim_Product  
- Dim_Geography  
- Dim_ShipMode  
- Dim_Date (Role-playing date dimension)

### ⭐ Advanced Modeling Features

- Active relationship: `Order Date → Dim_Date`
- Inactive relationship: `Ship Date → Dim_Date`
- DAX measure using `USERELATIONSHIP()` for Ship Date analysis
- Clean surrogate key implementation
- Optimized star schema relationships

---

## 📈 Dashboard Features

The interactive dashboard includes:

### 💰 KPI Cards
- Total Sales  
- Total Profit  
- Profit Margin %

### 📊 Performance Analysis
- Sales by Category  
- Profit Margin by Region  
- Sales by Region  
- Monthly Sales Trend (Order Date)  
- Monthly Sales Trend (Ship Date)  
- Delivery Days by Ship Mode  

### 🎛 Interactive Slicers
- Year  
- Region  
- Category  
- Segment  
- Ship Mode  

---

## 📌 Key Business Insights

- Generated **$16M in revenue** with **$1.94M profit (12% margin)**.  
- West and East regions are primary revenue drivers.  
- Central region shows **low profitability (4% margin)** despite strong revenue share.  
- Sales exhibit strong **Q4 seasonality**.  
- Delivery performance varies significantly by shipping mode.  
- Revenue is evenly distributed across product categories.  

---

## 🛠 Tools & Technologies

- Microsoft Excel (Professional Plus 2024)  
- Power Query (ETL)  
- Power Pivot (Data Modeling)  
- DAX (Data Analysis Expressions)  
- PivotTables & PivotCharts  

---

## 🎯 Skills Demonstrated

- Data Cleaning & Transformation  
- Star Schema Modeling  
- Surrogate Key Implementation  
- Relationship Management (Active/Inactive)  
- Role-Playing Date Dimension  
- DAX Calculations  
- KPI Design  
- Business Insight Generation  
- Executive Dashboard Design  

---

## 🚀 Project Objective

To design a scalable and structured data model that supports:

- Financial analysis  
- Regional performance monitoring  
- Operational evaluation  
- Time intelligence reporting  
- Executive-level decision making  

---

## 📂 File Structure
