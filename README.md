# 🚴 AdventureWorks Cycles Sales Analytics Dashboard | Advanced Excel Business Intelligence Project

> **An end-to-end Business Intelligence solution built entirely in Microsoft Excel using AdventureWorks Cycles sales data.**

---

## 📌 Project Overview

This project demonstrates a complete business intelligence workflow in **Microsoft Excel**, transforming raw transactional data into an interactive executive dashboard for strategic decision-making.

The solution leverages **Power Query**, **Power Pivot**, **DAX**, and advanced Excel analytics to uncover insights into sales performance, profitability, customer behavior, product performance, and regional trends.

The dashboard is designed to replicate the type of reporting used by sales managers, finance teams, and business analysts for monitoring KPIs and identifying growth opportunities.

---

# Dashboard Preview

## 📈 Time Analysis Dashboard

![Time Dashboard](images/report1.png)

---

## 📊 Product & Customer Performance Dashboard

![Performance Dashboard](images/report1.png)

---

# Business Objectives

The primary objectives of this project were to:

- Transform raw sales data into an analytics-ready data model
- Build interactive executive dashboards
- Track sales and profitability KPIs
- Identify high-performing products and customers
- Analyze customer demographics
- Discover seasonal and regional sales trends
- Enable dynamic filtering for business users
- Provide actionable insights for strategic decision-making

---

# Dataset Information

The project uses the **AdventureWorks Cycles** dataset containing multiple relational tables:

| Table       | Description                    |
| ----------- | ------------------------------ |
| Sales       | Order transactions             |
| Products    | Product catalog and categories |
| Customers   | Customer demographics          |
| Territories | Sales regions                  |
| Calendar    | Date dimension                 |

The dataset simulates real-world retail operations and contains thousands of sales transactions across multiple years.

---

# Tech Stack

- Microsoft Excel
- Power Query (ETL)
- Power Pivot
- Data Model
- DAX (Data Analysis Expressions)
- Pivot Tables
- Pivot Charts
- Slicers
- Timeline Filters
- Conditional Formatting

---

# Project Workflow

```
Raw Excel Data
        │
        ▼
Power Query
(Data Cleaning & Transformation)
        │
        ▼
Data Model (Power Pivot)
        │
        ▼
Relationships & Star Schema
        │
        ▼
DAX Measures
        │
        ▼
Interactive Dashboards
        │
        ▼
Business Insights
```

---

# Data Preparation

The dataset was cleaned and transformed using **Power Query**.

### Cleaning Tasks

- Removed duplicate records
- Corrected inconsistent data types
- Standardized column names
- Replaced missing values
- Generated Calendar Table
- Created Age Groups
- Created Income Groups
- Created Product Size Categories
- Created Profit & Margin calculations

---

# Data Modeling

A Star Schema model was implemented.

### Fact Table

- Sales

### Dimension Tables

- Customers
- Products
- Calendar
- Territories

Relationships were created using **Power Pivot** to support efficient filtering and aggregation.

---

# DAX Measures

The following measures were created:

- Total Revenue
- Total Cost
- Total Profit
- Profit Margin %
- Average Order Value
- Total Orders
- Units Sold
- Year-over-Year Revenue Growth
- Year-over-Year Profit Growth
- Running Total Revenue
- Profit Contribution %
- Top N Products
- Top N Customers

---

# Dashboard Features

## Executive KPIs

- Revenue
- Profit
- Cost
- Profit Margin
- Orders
- Quantity Sold
- Average Order Value

---

## Time Analysis Dashboard

Provides insights into:

- Revenue trend
- Profit trend
- Monthly analysis
- Quarterly performance
- Year-over-Year growth
- Weekday vs Weekend sales
- Seasonal trends

---

## Product Performance Dashboard

Analyzes

- Top Products
- Product Categories
- Product Colors
- Product Sizes
- Product Profitability
- Product Contribution %

---

## Customer Analytics

Analyzes

- Top Customers
- Age Groups
- Gender Distribution
- Income Groups
- Customer Profitability

---

## Geographic Analysis

Analyzes

- Country-wise Sales
- Regional Profit
- Territory Performance
- Regional Growth

---

# Business Questions Answered

### Sales Performance

- Which year generated the highest revenue?
- Which quarter contributed the highest profit?
- Which month recorded peak sales?
- How has revenue changed over time?

### Product Analysis

- Which products generate maximum profit?
- Which product category performs best?
- Which colors drive the highest sales?
- Which product sizes contribute most?

### Customer Analysis

- Who are the Top 5 customers?
- Which age group spends the most?
- Which income group is most profitable?
- What is the average customer age?

### Profitability

- What is the overall profit margin?
- Which products have the highest margins?
- Which regions generate maximum profit?

### Geographic Analysis

- Which country generates the highest revenue?
- Which territories are underperforming?
- Which regions have the fastest growth?

---

# Key Insights

Some notable business insights derived from the dashboard include:

- Revenue exhibits clear seasonal trends with stronger performance during specific months.
- A small number of products contribute a significant portion of total profit.
- High-income customer segments generate substantially higher average profits.
- Certain territories consistently outperform others across multiple years.
- Profit growth does not always align with revenue growth, emphasizing the importance of margin analysis.
- Customer demographics reveal opportunities for targeted marketing strategies.

---

# Skills Demonstrated

- Advanced Excel
- Business Intelligence
- Data Cleaning
- Data Transformation
- Data Modeling
- Power Query
- Power Pivot
- DAX
- KPI Reporting
- Dashboard Design
- Data Visualization
- Executive Reporting
- Business Storytelling
- Analytical Thinking

---

# Repository Structure

```
AdventureWorks-Excel-Dashboard/
│
├── Data/
│   ├── AdventureWorks.xlsx
│
├── Images/
│   ├── report1.png
│   ├── report2.png
│
├── README.md
```

---

# Future Enhancements

- Forecasting using Excel Forecast Sheet
- Dynamic Top N parameter
- Scenario & What-If Analysis
- Interactive Drill-Through Navigation
- Automated data refresh using Power Query
- VBA-based dashboard automation
- Monthly KPI tracking

---

# Conclusion

This project demonstrates how Microsoft Excel can be used as a complete Business Intelligence platform for enterprise reporting. By integrating Power Query, Power Pivot, DAX, and interactive dashboards, the solution transforms raw sales data into meaningful insights that support data-driven decision-making.

The project reflects industry-standard analytics practices including ETL, data modeling, KPI reporting, executive dashboarding, and business storytelling, making it suitable for showcasing advanced Data Analyst skills in a professional portfolio.
