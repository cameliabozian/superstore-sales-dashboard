# 📊 Superstore Sales Analytics Dashboard

A multi-page interactive sales analytics report built with Power BI, analysing 4 years of retail sales data across products, customers, and regions. Designed to answer key business questions for sales leadership, operations, and marketing teams.

---
## 📁 Data Source

The dataset used in this project is the **Sample Superstore Sales dataset** provided by Tableau Public.

- **Source:** [Tableau Public Sample Data](https://public.tableau.com/app/learn/sample-data)
- **Dataset:** Sample - Superstore
- **Records:** ~10,000 orders
- **Time Period:** 2023-2026
- **Geography:** United States
- **Fields:** 18 columns including Order ID, Sales, Profit, Quantity, Discount, Category, Sub-Category, Segment, Ship Mode, Region, State

This is a fictitious retail dataset commonly used for business intelligence and analytics practice. It simulates a US-based superstore selling Furniture, Office Supplies, and Technology products across four regions.

---
## 📌 Project Overview

This project transforms raw transactional sales data into a 3-page interactive dashboard suite. Each page targets a different business audience, from executives to product managers and marketing analysts.

**Business questions this dashboard answers:**
- Is revenue growing year over year and at what rate?
- Which product categories and sub-categories are most profitable?
- Which products generate the most revenue?
- Does discounting actually improve sales or destroy margins?
- Which customer segments drive the most revenue?
- Are there seasonal patterns in sales we can plan around?
- Which regions and shipping methods are most efficient?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development and DAX measures |
| Power Query | Data cleaning and transformation |
| DAX | Calculated measures (Profit Margin, Total Orders) |

---

## 📊 Dashboard Pages

### Page 1: Sales Executive Overview
![Executive Overview](<Sales Executive Overview.png>)

High level KPI summary designed for leadership. Shows the full business performance at a glance with interactive year and segment filters.

**Key visuals:**
- 4 KPI cards: Total Sales ($2.33M), Total Profit ($292K), Total Orders (5K), Profit Margin (12.56%)
- Annual Sales Growth 2023-2026 - column chart showing consistent year over year growth
- Sales Distribution by State - bubble map showing geographic concentration
- Profit Breakdown by Category - Technology leads at $146K, Furniture barely profitable at $19K

**Key insight:** Sales have grown consistently every year with 2026 on track to be the strongest year. Technology is the most profitable category while Furniture is a drag on margins.

---

### Page 2: Product Sales Performance
![Sales Performance](<Product Sales Performance.png>)

Designed for product managers and category owners. Identifies which products and sub-categories to invest in and which to review.

**Key visuals:**
- Sales vs Profit by Sub-Category - side by side comparison revealing loss-making categories
- Top 10 Products by Revenue - Canon imageCLASS leads at $60K+
- How Discounting Erodes Profit Margin - scatter plot proving the discount-profit relationship

**Key insight:** Tables generate significant sales volume but lose $18K, a classic over-discounting problem. The scatter plot clearly shows profit margin turning negative above 20% discount across all categories.

---

### Page 3: Customer & Trends Analysis
![Customer Trends](<Customer and Trend Analysis.png>)

Designed for marketing and operations teams. Reveals customer behaviour patterns and seasonal trends.

**Key visuals:**
- Monthly Sales Trends by Year - multi-year line chart showing seasonality patterns
- Revenue by Customer Segment - Consumer segment drives 50%+ of total revenue
- Shipping Method Preference - Standard Class dominates with 3x more orders than Second Class
- Regional Sales Performance - West region leads, South significantly underperforms

**Key insight:** Strong and consistent seasonality with sales spiking every September and November/December across all years, suggesting Q4 promotions and back to school campaigns are working. The South region is a clear growth opportunity.

---

## 🔍 Data Quality Notes

- Dataset contains transactional retail sales data from 2023-2026
- Date columns verified and cleaned in Power Query
- All monetary values in USD
- Discount values range from 0 to 0.8 (0% to 80%)
- Negative profit values retained as they represent real business losses from over-discounting

---

## 💡 Key Business Insights Summary

| Finding | Implication |
|---|---|
| Tables sub-category loses $18K | Review pricing and discount strategy |
| Discounts above 20% turn profit negative | Cap discounts at 20% across all categories |
| Consumer segment = 50%+ of revenue | Prioritise consumer marketing spend |
| South region underperforms all others | Investigate sales team or market fit issues |
| Q4 spike consistent across all years | Plan inventory and staffing around November peak |
| 2026 tracking above all previous years | Business is in strong growth phase |

---

## 👩‍💻 Author

**Camelia-Andreea Bozian**
[LinkedIn](https://www.linkedin.com/in/camelia-andreea-bozian)  | [GitHub](https://github.com/cameliabozian)
