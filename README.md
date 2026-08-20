# Superstore Sales & Business Intelligence Dashboard

AnalystLab Africa | Data Analytics Internship Programme  
Week 2: Business Intelligence & Interactive Dashboard Development  
Week 3: Advanced Data Analysis, KPI Development & Business Intelligence Dashboard

## Overview

This project started in Week 2 as a Power BI dashboard focused on understanding sales, profit, customers, and regional performance for a retail business.

In Week 3, I continued working on the same dashboard and added more detailed analysis. I looked deeper into the effect of discounts on profit, investigated the underperformance of the South region, and added time-based analysis to better understand sales and profit trends.

I also added new KPIs, DAX measures, and more interactive features to make the dashboard easier to explore and use for decision-making.

## Dataset

- Source: Superstore Sales Dataset (Kaggle)
- Rows: 9,994
- Columns: 21
- Period: 2014–2017
- Data includes: Order details, customers, products, categories, sub-categories, regions, sales, discounts, and profit.

## Dashboard Pages

The dashboard has 6 pages:

### 1. Sales & Regional Performance

- 5 KPI cards
- Sales by region
- Profit by region
- Monthly sales trend
- Sales distribution by state

### 2. Category & Customer Analysis

- Sales by category
- Category sales share
- Sales by customer segment
- Sub-category sales and profit breakdown

### 3. Executive Summary & Insights

This page summarizes the main findings from the Week 2 analysis, including key business insights, risks, opportunities, and recommendations.

### 4. Discount & Profitability Analysis - Week 3

- Discount vs. profit by sub-category
- Top 10 sub-categories by average discount
- Sub-category profitability and discount summary

### 5. Regional Deep-Dive - Week 3

- Sales vs. profit by state in the South region
- Sales by category in the South region
- Performance comparison across all four regions

### 6. Time-Based Analysis - Week 3

- Sales trend from 2014–2017
- Monthly sales and profit trends
- Sales Growth KPI

## KPIs

The dashboard tracks:

- Total Sales
- Total Profit
- Total Orders
- Average Sales
- Profit Margin
- Sales Growth (YoY)

## DAX Measures

I created DAX measures for:

- Total Sales
- Total Profit
- Total Orders
- Average Sales
- Profit Margin
- Sales Growth (Year-over-Year)

The Sales Growth measure uses SAMEPERIODLASTYEAR to compare performance with the previous year.

## Interactivity

To make the dashboard easier to explore, I added slicers across different pages:

- Region and Order Date slicers on Page 1
- Category and Segment slicers on Page 2
- Year slicers on Pages 4 and 5
- Region slicer on Page 6

## Key Findings from Week 3

- Sales increased by 46.88% between 2014 and 2017, but profit did not increase at the same pace. This suggests that higher sales did not necessarily translate into stronger profitability.
- Discounts have a clear negative relationship with profitability. For example, Bookcases had an average discount of 21% and generated a net loss despite recording $114,880 in sales.
- Florida, North Carolina, and Tennessee recorded strong sales but still made losses. This shows that high sales volume alone does not always mean good business performance.
- The South region had the lowest profit margin at 11.93%, compared with 14.94% in the West region, even though their order volumes were relatively comparable.
- Sales showed a clear seasonal pattern, with lower sales around February–June and stronger performance from September–December.

## Deliverables

- Power BI Dashboard (`.pbix`)
- Dashboard PDF Export
- Project Continuity Summary
- Business Insights & Recommendations Report
- DAX Measures Documentation
- This README

## Author

Adeleke Jubril Adedeji  
Data Analytics Intern — AnalystLab Africa
