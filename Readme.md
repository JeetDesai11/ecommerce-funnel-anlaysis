# User Journey & Conversion Funnel Analysis

 **Note:** This project was completed in **November–December 2025** and was later uploaded to GitHub for portfolio and documentation purposes.

## Overview

This project analyzes customer behavior across an e-commerce purchase funnel using **Google BigQuery SQL** and **Power BI**. The objective was to identify where users drop off during the purchasing journey, evaluate conversion performance, and generate actionable business insights to improve customer acquisition and revenue generation.

---

## Business Objective

The main objectives of this project are:

- Analyze customer progression through the e-commerce funnel
- Identify conversion bottlenecks and drop-off points
- Evaluate revenue performance by traffic source, product category, customer type, and device
- Compare behavior between new and returning customers
- Build an interactive Power BI dashboard for business decision-making

---

## Dataset

This project uses the **Google Analytics Sample E-commerce Dataset** available in BigQuery.

The dataset includes:

- User IDs and session IDs
- Traffic sources
- Product interactions
- Page views
- Checkout actions
- Transactions
- Revenue
- Device and browser information

---

## Technologies Used

- SQL
- Google BigQuery
- Power BI
- Google Analytics Data

---

## Project Structure

```text
ecommerce-funnel-analysis/
│
├── Dashboard/
│   └──  BI file.pbix
│  
│
├── sql_queries/
│   ├── a.revenue_trends.sql
│   ├── b.traffic_source_analysis.sql
│   ├── c.product_category_analysis.sql
│   ├── d.customer_segmentation.sql
│   ├── e.device_performance_analysis.sql
│   ├── f.session_funnel_analysis.sql
│   └── g.user_funnel_analysis.sql
│   
│
├── screenshots/
│   ├── Device Analysis.png
│   ├── Funell Analysis.png
│   ├── Monthly and daily Revenues.png
│   ├── Product Analysis.png
│   ├── Revenue by Traffic Source.png
│   ├── User level funell analysis.png
│   ├── Visitor Type Analysis.png
│   ├── Visualization Image.png
│   └── sample schema.png
│   
│
└── README.md
```
