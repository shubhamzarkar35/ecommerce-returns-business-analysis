# E-commerce Returns & Customer Behavior Analysis (Q4 2024)

## Project Overview
This project is an end-to-end business analysis of e-commerce order data focused on
understanding **why return rates are high** and **which customer, channel, and payment
segments contribute most to operational risk**.

Instead of only building dashboards, the objective of this project was to analyze
business KPIs such as **Average Order Value (AOV)**, **Return Rate**, and **RTO Rate**
and convert insights into **practical business recommendations**.

The analysis was performed entirely in **Microsoft Excel**, following a structured
analytics workflow used in real business environments.

---

## Business Questions Addressed
- What is driving the high overall return rate?
- How do returns differ by customer type (new vs returning)?
- Which order sources and product categories are most risky?
- How does Cash on Delivery (COD) compare to prepaid payments?
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

The dataset was cleaned, validated, and analyzed before building visualizations.

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
- The overall return rate is **~55%**, indicating a major operational challenge
- **Size-related issues account for ~37% of all returns**, making it the top return driver
- **New customers from Instagram Shop show the highest return rates**
- **COD orders are extremely risky**, with:
  - Return rate of **82.6%**
  - RTO rate of **25.8%**
- Returning customers have **lower return rates and higher AOV**, indicating better
  product understanding and purchase intent

---

## Recommendations
Based on the analysis, the following business actions are recommended:

- Reduce COD exposure for high-risk segments such as new customers and social commerce
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
- Carefully selected correct denominators for each KPI
  (Delivered orders vs Shipped orders)

### Data Visualization
- Built a clean dashboard with:
  - Weekly Delivered Orders vs Return Rate trend
  - Return Rate by Product Category
  - Return Reason Breakdown
  - Customer Type × Order Source comparison
  - COD vs Prepaid risk comparison
- Applied consistent color themes and formatting
- Designed charts for storytelling and decision-making

---

## Project Structure
The Excel workbook is organized as follows:

- **Raw_Data** – Original dataset
- **Validation_Summary** – Data quality checks
- **Working_Analysis** – Pivot tables and calculations
- **Visualization** – Final charts and dashboard
- **Analysis** – Business interpretation
- **Recommendations** – Actionable business suggestions

---

## What This Project Demonstrates
- Strong understanding of business KPIs
- Ability to segment customers and channels meaningfully
- Clear thinking around operational and fulfillment risk
- End-to-end analytics workflow using Excel
- Translating data insights into business decisions

---

## 👨‍💻 Author

**Shubham Zarkar**  
Aspiring Data Analyst | Python • SQL • Power BI  

---

### ⭐ Thanks for checking out the project!

If you found this project useful, feel free to **star ⭐ the repository**, fork it, or use it as inspiration for your own analytics portfolio.

