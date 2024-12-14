# Microsoft Fabric Project: Uber Performance Analysis

## 🚀 Overview
This project leverages **Microsoft Fabric** to analyze Uber's performance and gain actionable insights from raw data. Built as part of the **KSR Datavizon Microsoft Fabric Bootcamp**, it demonstrates the power of advanced data engineering and analytics.

---

## 🎯 Project Goal
Transform diverse raw datasets into meaningful trends and insights through robust data pipelines, scalable architecture, and interactive visualizations.

---

## 🔧 Tools and Technologies
- **Microsoft Fabric**: Unified platform for scalable data engineering and analytics.
- **Power BI**: Create dynamic, interactive visualizations and dashboards.
- **Data Sources**: SQL, Excel, JSON, CSV, and XML for comprehensive data analysis.

---

## 🏗️ Architecture
The project utilizes the **Medallion Architecture**, organized into three layers:

1. **Bronze Layer**: Raw data is ingested into the **Lakehouse** using the Copy Data activity, preserving its original format for traceability.
2. **Silver Layer**: Data is cleaned and transformed with **Dataflow Gen2**, addressing missing values, type conversions, and more.
3. **Gold Layer**: Analytical data pipelines ensure data is ready for reporting and advanced analysis.

---

## 📊 Features and Insights
1. **Lakehouse Architecture**: Designed for secure and scalable data storage.
2. **On-Premises Gateway**: Enabled seamless integration of on-premises data.
3. **Automated Data Pipelines**: Streamlined data processing workflows.
4. **Data Warehouse and OLAP Model**: Built for advanced analytics and real-time reporting.
5. **Interactive Power BI Dashboard**: Includes KPIs and insights such as:
   - Rides Completed
   - Total Users
   - Driver Earnings
   - Average Fare
   - Fare per KM
   - Revenue
   - Driver Ratings
   - Total Distance
6. **Insights Derived**:
   - Weekday vs. Weekend ride trends.
   - Revenue patterns .
   - Analysis of long-distance rides.



