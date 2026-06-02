# Olist E-Commerce Logistics Performance & Delivery Efficiency Audit

This repository contains production-ready SQL queries and the core Power BI template used to audit and evaluate the logistics performance of Olist E-Commerce (2017–2018).

## Analytics Workflow & Documentation
The data extraction, handling, and analysis were fully performed using MySQL. The final reporting, data modeling (Star Schema), and dynamic visualizations were built using Power BI. The core objectives focus on identifying critical route failures, analyzing lead time breakdowns, and mapping geographic bottlenecks.

---

## Dataset Source

The analysis is built upon the **Brazilian E-Commerce Public Dataset by Olist**, which contains real, anonymized commercial data from 100k orders structuralized between 2016 and 2018 in Brazil. 

* **Source Platform:** Kaggle
* **Dataset Link:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## Repository Contents

### 1. SQL Production Code (`queries.sql`)
A consolidated, heavily-commented production script containing the 5 core analytical queries executed during the audit:
* **Delivery Delay Evaluation & SLA Compliance Rate:** Analyzes the baseline Service Level Agreement (SLA) success metrics.
* **Fulfillment Lifecycle & Lead Time Breakdown:** Breaks down the end-to-end supply chain transit duration.
* **Macro-Corridor Matrix:** State-to-state performance and cross-regional risk mapping.
* **Micro-Geographic Deep Dive:** Localized city-level bottleneck identification (SP to RJ corridor).
* **Customer Experience Correlation:** Core evaluation of how delivery delays directly affect customer review scores.

### 2. Power BI Template (`Olist_Logistics_Audit.pbit`)
To adhere to data engineering and version control best practices, the Power BI architecture is provided as a lightweight template file (`.pbit`). 
* **What is included:** This file contains the complete interactive User Interface (UI/UX) layout, data model schemas (Star Schema relationships), and advanced DAX calculated measures without embedding the heavy raw dataset rows.
* **How to use:** Simply download the `.pbit` file, open it via Power BI Desktop, and input your localized Olist database credentials to automatically re-populate the live, interactive dashboards.
