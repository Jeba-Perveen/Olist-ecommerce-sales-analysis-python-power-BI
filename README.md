# Olist E-Commerce Sales Analysis & Business Intelligence Dashboard

## Table of Contents
- [Project Overview](#-Project-Overview)
- [Objectives](#-Objective)
- [Tech Stack](#️-Tech-Stack)
- [Repository Structure](#-Repository-Structure)
- [Project Workflow](#-Project-Workflow)
- [Data Cleaning](#-data-cleaning)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Feature Engineering](#️-feature-engineering)
- [Dashboard Overview](#-dashboard-overview)
  - [Executive Overview](#1.-executive-overview)
  - [Operational & Customer Insights](#2️2-operational--customer-insights)
  - [Business Performance & Risk Analysis](#3️3-business-performance--risk-analysis)
- [Key Business Insights](#-key-business-insights)
- [Business Recommendations](#-business-recommendations)
- [👩‍💻 Author](#-author)

## Project Overview
This project presents an end-to-end analysis of the Olist Brazilian E-Commerce dataset using Python and Power BI. The objective was to transform raw transactional data into actionable business insights through data cleaning, exploratory data analysis (EDA), feature engineering, and interactive dashboard development.
The project demonstrates a complete analytics workflow, from preparing raw data to building business-ready dashboards that support data-driven decision-making.

## Objectives
- Clean and preprocess the e-commerce dataset to improve data quality.
- Perform exploratory data analysis to identify sales trends and customer behavior.
- Engineer meaningful business features for deeper analysis.
- Build interactive Power BI dashboards to monitor business performance.
- Generate actionable insights and recommendations to support business decisions.
  
## Tech Stack
- Category:	Tools
- Programming: Python
- Libraries:	Pandas, Matplotlib
- Visualization:	Power BI
- Environment: Jupyter Notebook
- Data Source	Olist Brazilian E-Commerce Dataset

## Repository Structure
### olist-ecommerce-sales-analysis
│
├── notebooks
│   ├── Data Cleaning.ipynb
│   ├── Exploratory Data Analysis.ipynb
│   └── Feature Engineering.ipynb
│
├── dashboard
│   └── Olist_Ecommerce_Sales_Dashboard.pbix
│
├── images
│   ├── executive_overview.png
│   ├── customer_insights.png
│   └── performance_analysis.png
│
├── Business_Report.pdf
│
└── README.md

## Project Workflow
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Dashboard Development
- Business Insights & Recommendations
  
### Data Cleaning
The dataset was thoroughly assessed to ensure data quality before analysis.
Key activities included:
- Handling missing values
- Validating primary and composite keys
- Converting date columns to datetime format
- Investigating duplicate records
- Performing business rule validation
- Flagging data quality issues without removing valid business records

### Exploratory Data Analysis
The analysis focused on understanding:
- Monthly sales trends
- Revenue by product category
- Revenue by state
- Payment method distribution
- Delivery performance
- Customer review patterns
- Order status distribution
- Correlation between business variables

### Feature Engineering
Several business-oriented features were created to enhance analysis, including:
- Delivery Days
- Shipping Days
- Delivery Delay
- Order Approval Hours
- Purchase Month & Quarter
- Weekend Orders
- Review Categories
- Order Value Segmentation
- High Value Orders
- Freight Percentage

### Dashboard Overview
The Power BI solution consists of three interactive dashboards.

#### 1.Executive Overview
Provides a high-level summary of business performance through KPIs including:
- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Review Score
- Delivery Performance

#### 2.Operational & Customer Insights
Focuses on customer behavior and operational efficiency through:
- Customer Review Distribution
- Shipping Performance
- Approval Time
- Delivery Performance
- Weekend vs Weekday Orders
- Average Delivery Time by State

#### 3.Business Performance & Risk Analysis
Monitors operational risks and logistics using:
- Cancellation Rate
- Order Completion Rate
- Freight Cost Analysis
- Revenue vs Freight Cost
- Cancellation by State
- Freight Cost by Payment Type

### Key Business Insights
- Generated 20.58M in total revenue from 99K orders.
- Bed, Bath & Table was the highest revenue-generating product category.
- Sao Paulo contributed the largest share of revenue.
- Credit Card was the preferred payment method, accounting for the majority of transactions.
- Approximately 93.66% of orders were delivered on time.
- The average customer review score was 4.02, indicating strong customer satisfaction.
- The business maintained a 97.13% order completion rate with a low cancellation rate of 0.63%.

### Business Recommendations
- Prioritize inventory for high-performing product categories.
- Improve logistics in regions with longer delivery times.
- Monitor states with relatively higher cancellation rates.
- Optimize freight costs while maintaining delivery performance.
- Use seasonal sales trends for demand forecasting and inventory planning.

### Author
## Jeba Perveen
