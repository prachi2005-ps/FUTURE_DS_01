# FUTURE_DS_01
# 📊 E-commerce Sales Dashboard (Power BI)

An interactive Power BI dashboard analyzing e-commerce sales data to uncover business insights like revenue trends, top-selling products, and customer behavior.

##Overview

This project visualizes key sales metrics using Power BI, enabling business owners to make informed decisions based on:

- 💰 **Total Revenue**
- 🛍️ **Total Orders**
- 📦 **Average Order Value**
- 📅 **Monthly & Yearly Sales Trends**
- 🗂️ **Top Products and Categories**
- 🌍 **Revenue by Country**

## 🚀 Features

- Cleaned and transformed raw Excel/CSV data.
- Created DAX measures for KPIs and aggregations.
- Built interactive visuals (bar, line, card, pie charts).
- Implemented filters, slicers, and drill-downs.
- Used Model View to manage relationships.

## ⚙️ Tools & Skills

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Data Cleaning & Modeling  
- Business Storytelling through Visuals  
- Time Series Analysis

## 📁   Folder Structure
E-Commerce Dataset
E-Commerce Dashboard

- Sample e-commerce transactional data with fields like:
  - `Invoice`, `Customer ID`, `InvoiceDate`, `Quantity`, `Price`, `Country`, `Description`


## 📈 Key Measures (DAX)

```DAX
Total Revenue = SUMX('Year 2009-2010', 'Year 2009-2010'[Quantity] * 'Year 2009-2010'[Price])
Total Orders = DISTINCTCOUNT(SalesData_AllYears[Invoice])
Average Order Value = [Total Revenue] / [Total Orders]
