# 🛒 ShoppingMart End-to-End Analytics Project | Microsoft Fabric

## 📌 Project Overview

This project demonstrates an end-to-end analytics solution built using Microsoft Fabric. It integrates structured and unstructured business data, processes it through a modern Lakehouse architecture, and delivers interactive Power BI dashboards for business decision-making.

The solution combines multiple data sources including orders, customers, products, customer reviews, social media, and web logs to generate analytics-ready datasets and actionable business insights.

---

## 🛠️ Technology Stack

- Microsoft Fabric
- OneLake
- Data Factory Pipelines
- Lakehouse
- PySpark Notebooks
- Power BI
- JSON Metadata
- SQL
- DAX

---

## 🏗️ Project Architecture

The project follows the Medallion Architecture:

- 🥉 **Bronze Layer** – Raw data ingestion from multiple sources
- 🥈 **Silver Layer** – Data cleansing, validation, and transformation
- 🥇 **Gold Layer** – Business-ready datasets optimized for analytics and reporting

---

## 🚀 Key Features

### Data Ingestion

- Built automated Data Factory pipelines
- Implemented metadata-driven ingestion using JSON configuration
- Configured dynamic file processing for scalable ingestion

### Data Transformation

- Processed data using PySpark notebooks
- Performed cleansing, standardization, and enrichment
- Generated analytics-ready datasets

### Data Modeling

- Organized data using Bronze, Silver, and Gold layers
- Built curated business tables for reporting
- Optimized datasets for Power BI

### Dashboard Development

Created interactive Power BI dashboards to visualize:

- Total Sales KPI
- Revenue Analysis
- Sales Trends
- Product Performance
- Customer Analysis
- Category-wise Sales
- Customer Sentiment Analysis
- Website User Engagement
- Executive KPI Dashboard

---

## 📊 Business Insights

The dashboard provides insights into:

- Overall sales performance
- Top-selling products
- Highest-value customers
- Category performance
- Customer sentiment from reviews
- Website traffic and user behavior
- Business trends over time

---

## 💡 Key Learnings

- Building end-to-end analytics solutions using Microsoft Fabric
- Implementing metadata-driven ETL pipelines
- Developing scalable Lakehouse architectures
- Transforming data using PySpark
- Designing interactive Power BI dashboards
- Delivering business insights through modern analytics platforms

---

## 🎯 Project Outcome

This project demonstrates how Microsoft Fabric can be used to build scalable analytics solutions by integrating data engineering, data transformation, and business intelligence into a unified platform. The solution enables efficient data processing and provides actionable insights through interactive reporting.

---

## 📷 Dashboard Preview

## 1️⃣ Solution Architecture
This project follows the Microsoft Fabric Lakehouse architecture, moving data through Bronze, Silver, and Gold layers before serving analytics in Power BI.

![Architecture](images/image%201.jpeg)

---

## 2️⃣ End-to-End Data Pipeline
The master pipeline orchestrates data ingestion, transformation, and visualization using Microsoft Fabric.

![Master Pipeline](images/image%202.jpeg)

---

## 3️⃣ Pipeline Orchestration
The orchestration pipeline invokes Bronze ingestion, Silver transformations, and Gold layer notebooks to automate the end-to-end workflow.

![Pipeline Orchestration](images/image%203.jpeg)

---

## 4️⃣ Bronze Layer Data Ingestion
Raw structured and unstructured datasets are ingested into the Bronze layer using metadata-driven Fabric pipelines.

![Bronze Layer](images/image%204.jpeg)

---

## 5️⃣ Gold Layer Transformations
PySpark notebooks aggregate and transform Silver data into analytics-ready Gold datasets.

![Gold Layer Notebook](images/image%205.jpeg)

---

## 6️⃣ Lakehouse Storage
Data is organized using the Medallion Architecture within OneLake, separating Bronze, Silver, and Gold datasets.

![Lakehouse](images/image%206.jpeg)

---

## 7️⃣ Power BI Dashboard
The final semantic model is visualized using an interactive Power BI dashboard featuring KPIs, sales trends, customer insights, product analysis, sentiment analysis, and web engagement metrics.

![Power BI Dashboard](images/image%207.jpeg)
---

## 👩‍💻 Author

**Atchaya Prabhu**

- LinkedIn: www.linkedin.com/in/atchayaprabhu17
- GitHub: https://github.com/Atchaya-Prabhu
