# 🌿 Plant Co. Quantity Performance Dashboard (Power BI)

This repository contains a Power BI report named **Plants[1].pbix**, created to analyze **plant-level quantity performance for 2024**.  
The dashboard provides an interactive exploration of key business metrics, including:

---

## 📊 Project Overview

The report focuses on the following analytics:

- **YTD (Year-to-Date) Quantity Performance**
- **PYTD (Previous Year-to-Date) Comparison**
- **Quantity vs PYTD Gap Analysis**
- **Country & Product Type Breakdown**
- **Monthly YTD vs PYTD Visualizations**
- **Profitability Segmentation (GP% vs Quantity)**

The goal of this dashboard is to support business decision-making by providing insights into **which countries, product types, and accounts contribute positively or negatively to overall performance**.

---

## 📁 File Included

- **Plants[1].pbix** — Main Power BI dashboard file  
  Contains visuals, DAX measures, data model, and all report pages.

---

## 🧩 Data Model

The report uses the following tables:

- `Dim_Account`
- `Dim_Date`
- `Dim_Product`
- `Fact_Sales`
- `Slc_Values`
- `_Measures` (calculated DAX measures)

A star-schema model is used for clean and efficient analysis.

---

## 🔧 Key Features

- Modern Power BI visuals (tree map, clustered column, bar charts, scatter plot)
- Interactive slicers (year, product type, etc.)
- DAX-based KPIs:
  - **YTD**
  - **PYTD**
  - **YTD vs PYTD Difference**
  - **GP% (Gross Profit Percentage)**

