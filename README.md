Markdown

# [BUSINESS KPI DASHBOARD]

---

## Table of Contents

- [1. Introduction](#1-introduction)
- [2. Features](#2-features)
- [3. Project Workflow](#3-project-workflow)
  - [3.1. Data Exploration And KPI Discovery](#31-data-exploration-and-kpi-discovery)
  - [3.2. Data Modeling in a Warehouse](#32-data-modeling-in-a-warehouse)
  - [3.3. Final Dashboard And Visualization](#33-final-dashboard-and-visualization)
- [4. Project Components](#4-project-components)

---

## 1. Introduction

This repository holds a portfolio project that demonstrates my ability to tackle a real-world business challenge under pressure. In this scenario, I'm the newly hired data professional at GoExplore, a rapidly growing company facing a data crisis. My task was to transform a single, raw spreadsheet into a dynamic KPI dashboard in just two weeks, providing the CEO with the tools to gain ongoing insights and better steer the company.

This project showcases my ability to move beyond just analyzing data to building a sustainable analytical framework. It highlights my skills in identifying key business metrics, using various tools from simple spreadsheets to structured data warehouses, and creating intuitive dashboards that empower non-technical leaders to make informed decisions.

---

## 2. Features

- **Business-Insights**: Demonstrates an understanding of business goals and the ability to identify relevant Key Performance Indicators (KPIs) from raw data.
- **Full Analytical Workflow**: Highlights a complete process from initial data exploration and cleaning to modeling, querying, and final visualization.
- **Versatile Tool Usage**: Showcases proficiency with a range of tools, including Google Sheets for quick analysis, BigQuery as a data warehouse, and Looker Studio for interactive dashboards.
- **Data Modeling Skills**: Explains the process of restructuring data into an OLAP-friendly star schema for efficient analysis.
- **Data Storytelling**: Focuses on building visuals that tell a clear story, ensuring insights are accessible to stakeholders without a technical background.

---

### 3. Project Workflow

This project was built following a logical progression from raw data to a final dashboard. This section outlines each key phase.

### 3.1. Data Exploration And KPI Discovery
The initial phase involved exploring the raw spreadsheet to understand the data and identify potential KPIs. Google Sheets was used as the primary tool for this. This stage focused on using pivot tables to summarize data and find insights that would be valuable to the CEO.

### 3.2. Data Modeling in a Warehouse
To move from a simple spreadsheet to a robust, scalable solution, the data was modeled for a data warehouse. This involved structuring the data into a star schema using BigQuery, which separates the facts (sales data) from the dimensions (products, retailers, etc.). This design is optimized for analytical queries, aligning with an OLAP approach to data.

### 3.3. Final Dashboard And Visualization
The final step was to build an interactive dashboard in Looker Studio. This tool was connected directly to the BigQuery queries, allowing for dynamic visualizations that bring the KPIs to life. The dashboard provides a clear, high-level overview of the company's performance, allowing the CEO to intuitively grasp key metrics.

---

### 4. Project Components

This section contains links to the key deliverables and resources from this project.

<details>
<summary>Initial Raw Data (Google Sheet)</summary>
<br>
This spreadsheet contains the raw data that served as the starting point for the entire project. It's where the initial exploration and KPI discovery took place.
<br>
<a href="https://docs.google.com/spreadsheets/d/1Ha5fPKU8lrVWPSfVkhw9XGEvXldpoc39vjFBeax_UO0/edit?gid=1031855285#gid=1031855285">View Google Sheet</a>
</details>

<details>
<summary>SQL Queries for BigQuery</summary>
<br>
The SQL queries used for this project demonstrate our process of transforming raw data into structured, analytical insights for the dashboard. Due to the data retention policy of the free BigQuery service, a screenshot of the queries has been preserved to document our work.
<br>
<a href="https://github.com/Cebulva/business-kpi-dashboard/blob/main/Screenshots/BigQueryRevenueQuery.png">View SQL Revenue Query</a>
</details>

<details>
<summary>Final KPI Dashboard (Looker Studio)</summary>
<br>
The final interactive dashboard built to provide the CEO with a clear, ongoing view of GoExplore’s performance. This dashboard visualizes the key metrics and insights derived from the data analysis.
<br>
<a href="https://lookerstudio.google.com/reporting/928e4db6-c643-41d3-a4b2-d90d151dd09a">View Dashboard</a>
</details>
