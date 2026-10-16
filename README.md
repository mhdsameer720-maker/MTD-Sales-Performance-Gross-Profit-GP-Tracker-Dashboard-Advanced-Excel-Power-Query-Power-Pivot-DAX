# Retail MIS: MTD Sales Performance & GP Tracker Dashboard

An end-to-end retail data analytics model built in Microsoft Excel to track Month-to-Date (MTD) sales, gross profit, target achievement, and stock position across 5 regions (UAE, KSA, Kuwait, Oman, and Qatar), categorized by store and merchandise category[cite: 1].

---

## 📊 Project Overview
Daily retail performance data was previously scattered across separate Excel files (sales, targets, last month, last year, and stock ageing), leading to manual consolidation bottlenecks and reporting delays[cite: 1]. This project replaces manual reporting with a fully automated, refreshable Excel model powered by Power Query, Power Pivot, and DAX[cite: 1].

## 🛠️ Tech Stack & Skills Used
* **Advanced Excel**: Dashboard design, KPI cards, slicers, and interactive reporting tables[cite: 1].
* **Power Query**: Automated ETL pipeline to clean data, fix data types, remove unneeded columns, and combine source files[cite: 1].
* **Power Pivot & Data Modelling**: Relational data modelling linking transactional and target tables to master dimension tables (`Store_WH`, `H2` category, and `Calendar`)[cite: 1, 7].
* **DAX (Data Analysis Expressions)**: 13 custom measures for advanced retail analytics[cite: 1].
* **Retail Analytics & MIS Reporting**: Tracking MTD performance, Month-over-Month (MoM) growth, average ticket size, and number of bills (NOB)[cite: 1].

---

## 🔄 How It Works (ETL & Data Architecture)
1. **Source Files**: Consolidates 7 source files including Sales, Target, Last Month, Last Year, and Stock Ageing records[cite: 1].
2. **Power Query Transformation**: Handles data cleansing, column restructuring, and merging workflows[cite: 1].
3. **Power Pivot Model**: Establishes a star/snowflake schema with active relationships between fact tables and dimensions (`Store_WH`, `Category`, `Calendar`)[cite: 1, 7].
4. **DAX Measures**: Implements dynamic calculations for KPIs such as:
   * `MTD Net Sales`[cite: 6]
   * `MTD Target` & `Target Ach%`[cite: 6]
   * `MTD GP` & `MTD GP Ach%`[cite: 1, 6]
   * `M-o-M Sale` & `M-o-M GP`[cite: 6]
   * `MTD NOB` (Number of Bills) & `Avg Ticket Size`[cite: 6]
5. **Interactive Dashboard**: Features summary cards, dynamic slicers, regional charts, store comparisons, and stock value analytics[cite: 1, 4].

## 📈 Business Impact
* **One-Click Reporting**: Replaces tedious manual consolidation with instant data refreshes[cite: 1].
* **Inventory & Sales Alignment**: Combines sales data with stock values to optimize replenishment and stock-ageing decisions[cite: 1].
* **Performance Visibility**: Provides management with a rapid breakdown of regional, store, and category-level variances against targets and historical benchmarks[cite: 1].
