# E-commerce Returns & Customer Behavior Analysis (Q4 2024)

## Project Overview
This project is an end-to-end business analysis of e-commerce order data focused on
understanding **why return rates are high** and **which customer, channel, and payment
segments contribute most to operational risk**.

The goal of this project was not just to build dashboards, but to analyze key business
KPIs such as **Average Order Value (AOV)**, **Return Rate**, and **RTO Rate**, and translate
those insights into **clear, actionable business recommendations**.

The entire analysis was performed using **Microsoft Excel**, following a structured
analytics workflow similar to real-world business analysis projects.

---

## Dashboard Preview

![Dashboard Overview](Dashboard.png)

---

## Business Questions Addressed
- What is driving the high overall return rate?
- How do returns differ by customer type (new vs returning)?
- Which order sources and product categories contribute most to returns?
- How risky are Cash on Delivery (COD) orders compared to prepaid orders?
- What actions can the business take to reduce returns and operational costs?

---

## Dataset Overview
- Time period: **Q4 2024**
- Total orders analyzed: **346**
- Data includes:
  - Order details
  - Customer type
  - Order source
  - Payment method
  - Product category
  - Delivery and return status
  - Return reasons

The dataset was cleaned, validated, and analyzed before creating visualizations.

---

## Key Metrics Analyzed
- Gross Merchandise Value (GMV)
- Net Revenue
- Average Order Value (AOV)
- Return Rate
- RTO (Return to Origin) Rate
- Customer and channel-level performance

---

## Key Insights
- The overall return rate is **~55%**, indicating a significant operational challenge
- **Size-related issues account for ~37% of all returns**, making it the largest return driver
- **New customers from Instagram Shop show the highest return rates**
- **COD orders are extremely high-risk**, with:
  - Return rate of **82.6%**
  - RTO rate of **25.8%**
- Returning customers have **lower return rates and higher AOV**, showing better product
  understanding and purchase intent

---

## Recommendations
Based on the analysis, the following actions are recommended:

- Reduce COD exposure for high-risk segments such as new customers and social commerce orders
- Improve size and fit communication for apparel categories like Outerwear and Dresses
- Re-evaluate Instagram Shop acquisition quality and shift focus to Website and Mobile App
- Use returning customers as a benchmark for healthy return behavior

These actions can help reduce reverse logistics costs without negatively impacting growth.

---

## Tools & Techniques Used

### Microsoft Excel
- Primary tool used for the complete analysis

### Data Cleaning
- Removed duplicates and handled missing values
- Standardized categorical fields
- Created helper columns for:
  - Customer Type (New vs Returning)
  - Payment Type (COD vs Prepaid)

### Data Validation
- Built a Validation Summary sheet with pass/fail checks
- Verified totals for orders, returns, GMV, and revenue
- Ensured consistency across raw data, pivots, and final metrics

### Analysis & Calculations
- Used Pivot Tables to analyze:
  - Weekly trends
  - Product categories
  - Customer segments
  - Payment methods
- Calculated:
  - AOV
  - Return Rate
  - RTO Rate
- Used correct denominators for each KPI
  (Delivered orders vs Shipped orders)

### Data Visualization
- Created insight-driven charts including:
  - Weekly Delivered Orders vs Return Rate
  - Return Rate by Product Category
  - Return Reason Breakdown
  - Customer Type × Order Source comparison
  - COD vs Prepaid risk analysis
- Designed a clean, dashboard-style Visualization sheet

---

## Project Structure
The Excel workbook is organized into the following sheets:

- **Raw_Data** – Original dataset
- **Validation_Summary** – Data quality and consistency checks
- **Working_Analysis** – Pivot tables and calculations
- **Visualization** – Final dashboard and charts
- **Analysis** – Business interpretation
- **Recommendations** – Actionable business suggestions

---

## What This Project Demonstrates
- Strong understanding of business KPIs
- Customer and channel segmentation skills
- Ability to identify operational and fulfillment risks
- End-to-end Excel-based analytics workflow
- Translating data insights into business decisions

---

## 👨‍💻 Author

**Shubham Zarkar**  
Aspiring Data Analyst | Python • SQL • Power BI  

---

### ⭐ Thanks for checking out the project!

If you found this project useful, feel free to **star ⭐ the repository**, fork it, or use it as inspiration for your own analytics portfolio.
