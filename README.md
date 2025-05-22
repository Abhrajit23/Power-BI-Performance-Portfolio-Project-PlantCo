
# 📊 Power BI Performance Portfolio Project – PlantCo

### By: Abhrajit Das

---

## 🔍 Project Overview

This Power BI project delivers a complete **end-to-end business performance dashboard** for a fictional company named *PlantCo*. The report provides deep insights into sales, gross profit, quantity sold, and account-level profitability using advanced **DAX**, **dynamic measures**, and **interactive visualizations**.

This project was designed to serve as an **excellent portfolio piece**, showcasing your ability to build real-world BI solutions using:

* Power Query
* Data modeling with fact/dimension tables
* Switch measures for dynamic KPIs
* Year-to-date (YTD) and prior year comparisons
* Conditional formatting
* Dynamic report and visual titles
* Custom scatter chart segmentation

---

## 📁 Dataset Structure

The Excel dataset contains **three primary tables**:

| Table Name    | Description                                                                 |
| ------------- | --------------------------------------------------------------------------- |
| `fact_sales`  | Sales invoice data with fields like Product ID, Quantity, Price, COGS, Date |
| `dim_account` | Customer metadata including Country, Account ID, Location                   |
| `dim_product` | Product hierarchy including Family, Group, Type, Size                       |

Also includes a custom `dim_date` table created in Power BI.

---

## ⚙️ Key Features

### 🧱 Data Modeling

* Renamed tables to follow fact/dim convention
* Removed duplicates from dimension keys
* Created a robust `dim_date` calendar table
* Added "In Past" flag column to handle partial-year comparisons
* Created a slicer values table (`SLC_Values`) for switch-based KPI controls

---

### 🧮 DAX Measures

* **Base KPIs:** `Sales`, `Quantity`, `Gross Profit`
* **YTD/ Prior YTD:** Dynamic measures with correct date logic using `SAMEPERIODLASTYEAR()` and `TOTALYTD()`
* **Switch Measures:** Allow toggling between different metrics using slicer
* **Comparison Measure:** `YTD vs Prior YTD` delta
* **Gross Profit %:** Custom profitability metric

---

## 📊 Report Pages & Visuals

### 📌 Header Section

* KPI Cards for: YTD, Prior YTD, Comparison, and GP%
* Slicer for dynamic metric selection
* Cleaned layout with conditional formatting (green/red deltas)

### 📈 Visuals

| Chart Type                 | Purpose                                                           |
| -------------------------- | ----------------------------------------------------------------- |
| **Tree Map**               | Bottom 10 countries by YTD vs PYTD performance                    |
| **Waterfall Chart**        | Drivers behind YTD vs PYTD performance gaps                       |
| **Line + Stacked Column**  | Monthly trends by product type with drill-down to quarters/months |
| **Scatter Chart (Zoomed)** | Account segmentation by GP% vs Sales/Quantity with average lines  |

---

### 🎨 Report Design Features

* Custom PowerPoint background for a clean, branded layout
* Dynamic chart & report titles based on slicer selections
* Shadowing, soft greys, and rounded card visuals for modern UX
* Zoom slider for scatter chart to handle large volumes of accounts

---

## 💼 Use Case Summary

This Power BI report is designed to simulate **real-world decision-making scenarios** in a product-based company. Key takeaways:

* Identify underperforming regions or products
* Spot high-GP% accounts with low volume for upselling
* Understand which months or quarters require attention
* Use data storytelling to recommend actionable strategies

---

## 📷 Dashboard Preview
![PlantCo Dashboard](https://github.com/Abhrajit23/Power-BI-Performance-Portfolio-Project-PlantCo/raw/main/Dashboard.png)

---

## ✅ Tools Used

* **Power BI Desktop**
* **DAX**
* **Power Query**
* **Microsoft Excel (source data)**
* **ChatGPT (for DAX cleanup & explanations)**

---

## 📝 How to Use

1. Clone or download the repo
2. Open the `.pbix` file in Power BI Desktop
3. Explore slicers and visuals to understand metric behavior
4. Adapt the project for your own company, domain, or case study

---

## 🎓 Learning Goals

* Build **clean and efficient data models**
* Apply **advanced DAX concepts** like SWITCH, YTD, SAMEPERIODLASTYEAR
* Use **interactive slicers** and **dynamic titles** for user-driven storytelling
* Format visuals with **conditional logic and best practices**
* **Segment and prioritize** insights using scatter plots and KPIs

---

## 📬 Contact

💼 **Abhrajit Das**
📧 [abhrajit.breathin@gmail.com](mailto:abhrajit.breathin@gmail.com)
🌐 [Open-talk.co](https://open-talk.co) | [LinkedIn](https://www.linkedin.com)

