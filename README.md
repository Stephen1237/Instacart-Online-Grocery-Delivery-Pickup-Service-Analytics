# Instacart-Online-Grocery-Delivery-Pickup-Service-Analytics
This Business Intelligence capstone project analyzes Instacart's sales and operations using SQL and Power BI. It uncovers insights into revenue, customer behavior, product performance, demand trends, and profitability, providing data-driven recommendations to optimize inventory, staffing, marketing, and overall business performance and growth.

---

# Instacart Online Grocery Delivery & Pickup Service Analytics
## Business Intelligence Capstone Project using Power BI & SQL

---

# Table of Contents

1. Project Introduction
2. Problem Statement
3. Project Overview
4. Business Objectives
5. Dataset Overview
6. Tools & Technologies
7. Power BI Dashboard Analysis
   - Executive KPIs
   - Aisles by Customer Demand & Profitability
   - Best Performing Products
   - Worst Performing Products
   - Busiest Time of Day
   - Monthly Revenue Trends
8. SQL Business Analysis
   - Top 5 Departments by Revenue
   - Top 3 Products Sold During Weekends
   - Bread vs Alcohol Profitability
   - Products Not Sold
   - SQL Queries
9. Key Findings
10. Recommendations
11. Conclusion

---

# Project Introduction

Business Intelligence enables organizations to transform raw operational data into meaningful insights that support strategic decision-making. In today's competitive online grocery market, understanding customer purchasing behavior, product performance, and operational efficiency is essential for sustaining profitability and improving customer satisfaction.

This project analyzes **Instacart's** operational and transactional data using **SQL** for data extraction and business querying, and **Power BI** for data visualization and dashboard development. The objective is to uncover actionable insights that help management optimize product assortment, improve inventory planning, enhance customer experience, and drive long-term business growth.

---

# Problem Statement

Instacart processes millions of grocery orders across numerous product categories and departments. However, management lacks a centralized reporting solution that provides visibility into business performance and customer behavior.

The absence of a unified analytics platform creates several business challenges:

- Limited visibility into revenue performance.
- Difficulty identifying top-performing and underperforming products.
- Inability to understand customer purchasing patterns.
- Inefficient inventory planning.
- Poor workforce allocation during peak shopping periods.
- Limited insights into departmental profitability.
- Difficulty making informed strategic decisions.

To address these challenges, an interactive Business Intelligence solution was developed using SQL and Power BI.

---

# Project Overview

The project integrates transactional datasets to evaluate Instacart's sales performance and operational efficiency.

The analysis focuses on:

- Revenue analysis
- Customer purchasing behavior
- Product performance
- Department performance
- Aisle profitability
- Sales trends
- Peak shopping periods
- Business profitability

The final deliverable consists of an interactive Power BI dashboard supported by SQL-driven business analysis that enables stakeholders to monitor key business metrics and identify opportunities for growth.

---

# Business Objectives

- Analyze customer ordering behavior.
- Measure revenue and profitability.
- Identify high-performing and low-performing products.
- Evaluate departmental revenue contribution.
- Understand customer demand across aisles.
- Discover peak shopping hours.
- Monitor monthly revenue trends.
- Provide actionable business recommendations.

---

# Dataset Overview

The project utilizes relational datasets containing information on:

| Dataset | Description |
|----------|-------------|
| Orders | Customer transactions including order date, quantity, and purchase behavior |
| Products | Product information including pricing and cost |
| Departments | Product department classifications |
| Aisles | Product aisle categorization |

These datasets were integrated using SQL joins to generate meaningful business insights.

---

# Tools & Technologies

- **SQL (PostgreSQL)** – Data extraction and business analysis
- **Power BI** – Dashboard development and data visualization
- **Data Modeling** – Relationship building between tables

---

# Power BI Dashboard Analysis

## Executive KPIs

### Dashboard Metrics

| KPI | Value |
|------|-------:|
| Total Revenue | **$158.37 Million** |
| Total Orders | **1 Million** |
| Total Customers | **63,000** |
| Average Order Value | **$151.03** |
| Profit Margin | **10.0%** |

### Analysis

The dashboard provides a high-level overview of business performance. Instacart generated over **$158 million** in revenue from approximately **1 million orders**, serving **63,000 customers**. While the company maintains a healthy transaction volume, the **10% profit margin** indicates opportunities to improve profitability through pricing optimization, product mix enhancement, and operational efficiencies.

---

# Aisles by Customer Demand and Profitability

This visualization examines the relationship between customer demand and profitability across different product aisles.

## Key Findings

| Metric | Value |
|--------|-------|
| Revenue | $158.37M |
| Profit Margin | 10% |
| Demand-Profit Relationship | Strong Positive Correlation |
| High-Demand Low-Profit Categories | Staples, Beverages, Snacks |

### Business Insights

- Essential grocery items such as **rice, flour, and sugar** generate high sales volumes but relatively low profit margins due to competitive pricing.
- Beverage categories experience high demand but incur additional logistics costs that reduce profitability.
- Snack products contribute significant sales volume; however, promotional discounts limit their profit contribution.

---

# Best Performing Products

## Top Products

| Product | Approx. Revenue |
|----------|----------------:|
| Tender White | $10K |
| Chicken With | $10K |
| Chili With Beans | $10K |
| Vanilla Tang | $10K |
| Mediterranean | $10K |

## Key Findings

- The top five products generated approximately **$10K** each.
- Revenue distribution among these products is relatively balanced.
- The business is not overly dependent on a single product for revenue generation.

### Business Insight

A diversified product portfolio minimizes business risk and provides opportunities for strategic cross-selling and promotional campaigns.

---

# Worst Performing Products

## Lowest Performing Products

| Product | Approx. Revenue |
|----------|----------------:|
| Seeded Mu | <$200 |
| Buttermilk | <$200 |
| Plus Cranb | <$200 |
| Duck Mous | <$200 |
| Caramel M | Near $0 |

## Key Findings

- Underperforming products contribute less than **$200** each.
- Caramel M recorded the lowest sales.
- These products consume inventory space while generating minimal returns.

### Business Insight

Management should evaluate product positioning, pricing, or discontinuation strategies for these items.

---

# Busiest Time of Day

## Customer Order Activity

| Time | Orders |
|------|-------:|
| 12 AM–2 AM | 2K–7K |
| 10 AM | 84K |
| 11 AM | 86K |
| 12 PM | 88K |
| 2 PM | Peak Demand |
| 10 PM | 12K |

## Key Findings

- Peak demand occurs between **10 AM and 2 PM**, reaching approximately **88,000 orders**.
- Overnight demand remains consistently low.
- Order volume declines steadily after the afternoon peak.

### Business Insight

Optimizing workforce scheduling and delivery capacity during peak hours can improve operational efficiency and customer satisfaction.

---

# Monthly Revenue Trends

## Monthly Revenue

| Month | Revenue |
|-------:|---------:|
| Month 0 | $14.6M |
| Month 1 | $13.8M |
| Month 2 | $14.6M |
| Month 3 | $12.6M |
| Month 4 | $12.6M |
| Month 5 | $13.1M |
| Month 6 | $12.6M |
| Month 7 | $13.0M |

## Key Findings

- Highest monthly revenue reached **$14.6M**.
- Lowest monthly revenue was **$12.6M**.
- Revenue fluctuated by approximately **$2M**.
- Monthly revenue stabilized around **$13M**.

### Business Insight

Understanding the factors behind revenue peaks and declines will help management improve forecasting and implement more effective promotional strategies.

---

# SQL Business Analysis

## 1. Top Five Departments by Revenue

### Key Findings

| Department | Revenue |
|------------|---------:|
| Personal Care | >$20M |
| Pantry | High |
| Snacks | High |
| Beverages | Moderate |
| Frozen | Lowest among Top 5 |

### Analysis

Personal Care emerged as the highest revenue-generating department, contributing more than **$20 million** in sales. While this reflects strong customer demand, it also highlights a concentration risk, suggesting opportunities to strengthen lower-performing departments.

### SQL Query

```sql
SELECT
    d.department,
    SUM(o.quantity * p.unit_price) AS total_revenue
FROM departments d
JOIN products p
    ON d.department_id = p.department_id
JOIN orders o
    ON p.product_id = o.product_id
GROUP BY d.department
ORDER BY total_revenue DESC
LIMIT 5;
```

---

## 2. Top Three Products Sold During Weekends

### Key Findings

| Product | Units Sold |
|----------|-----------:|
| Sparkling Blood Orange Soda | >100 |
| English Hydro Cucumber | >100 |
| Low-Moisture Part-Skim Mozzarella Cheese | >100 |

### Analysis

Weekend purchasing behavior is diversified across beverages, produce, and dairy, indicating opportunities for bundled promotions and targeted weekend campaigns.

### SQL Query

```sql
SELECT
    p.product_name,
    SUM(o.quantity) AS units_sold
FROM orders o
JOIN products p
    ON o.product_id = p.product_id
WHERE o.order_dow IN (0,6)
GROUP BY p.product_name
ORDER BY units_sold DESC
LIMIT 3;
```

---

## 3. Bread vs Alcohol Profitability

### Key Findings

| Category | Profitability |
|-----------|---------------|
| Alcoholic Products | Higher |
| Bread Products | Lower |

### Analysis

Alcoholic products generated slightly higher profits than bread products, reflecting stronger margins despite bread's consistent demand.

### SQL Query

```sql
SELECT
    CASE
        WHEN d.department = 'alcohol' THEN 'Alcoholic Products'
        WHEN p.product_name ILIKE '%bread%' THEN 'Bread Products'
    END AS category,
    SUM(o.quantity * (p.unit_price - p.unit_cost)) AS total_profit
FROM orders o
JOIN products p
    ON o.product_id = p.product_id
JOIN departments d
    ON p.department_id = d.department_id
WHERE d.department = 'alcohol'
   OR p.product_name ILIKE '%bread%'
GROUP BY 1;
```

---

## 4. Products Not Sold

### Key Findings

- **Zero products** were found without sales.
- Every product in the catalog recorded at least one transaction.
- Inventory utilization achieved **100% product coverage**.

### SQL Query

```sql
SELECT
    p.product_name
FROM products p
LEFT JOIN orders o
    ON p.product_id = o.product_id
WHERE o.product_id IS NULL;
```

---

# Overall Key Findings

| Metric | Result |
|--------|-------:|
| Total Revenue | **$158.37M** |
| Total Orders | **1 Million** |
| Total Customers | **63K** |
| Average Order Value | **$151.03** |
| Profit Margin | **10%** |
| Peak Shopping Hours | **10 AM – 2 PM** |
| Highest Monthly Revenue | **$14.6M** |
| Lowest Monthly Revenue | **$12.6M** |
| Revenue Variance | **$2M** |
| Highest Revenue Department | **Personal Care (> $20M)** |
| Weekend Best Sellers | **3 Products (>100 Units Each)** |
| Unsold Products | **0** |
| Best Performing Products | **≈ $10K Each** |
| Lowest Performing Products | **< $200 Each** |

---

# Recommendations

Based on the findings, the following recommendations are proposed:

### Product Portfolio Optimization
- Increase investment in high-performing products through targeted promotions and expanded inventory.
- Reassess underperforming products for repositioning, pricing adjustments, or discontinuation.

### Pricing and Profitability
- Review pricing strategies for high-demand, low-margin categories to improve profitability.
- Negotiate supplier costs and optimize promotional discounts to enhance gross margins.

### Inventory Management
- Align inventory levels with demand forecasts to minimize stockouts and overstock situations.
- Maintain sufficient stock of high-performing and weekend best-selling products.

### Workforce and Operations
- Allocate additional staff and delivery resources during peak demand hours (10 AM–2 PM).
- Optimize operational schedules to reduce costs during periods of low customer activity.

### Marketing Strategy
- Implement personalized promotions based on customer purchasing behavior.
- Introduce cross-selling and bundled offers that combine high-demand products with higher-margin items.
- Leverage seasonal campaigns to reduce monthly revenue fluctuations.

### Business Intelligence
- Continuously monitor KPIs through Power BI dashboards.
- Expand the analytics framework with predictive models to improve demand forecasting and support proactive decision-making.

---

# Conclusion

Great businesses are built on great decisions—and great decisions are powered by data. This project demonstrates how combining SQL for robust data analysis with Power BI for dynamic visualization can transform millions of transactional records into actionable business intelligence.

The analysis uncovered valuable insights into customer behavior, revenue performance, product profitability, and operational trends, providing a clear roadmap for improving efficiency, enhancing customer satisfaction, and maximizing profitability. From identifying peak shopping periods to highlighting high-performing products and revenue-driving departments, the findings empower stakeholders to make informed, evidence-based decisions with confidence.

More than a technical exercise, this project illustrates the strategic value of Business Intelligence in solving real-world business challenges. By turning raw data into meaningful insights and practical recommendations, it showcases how analytics can become a competitive advantage—enabling organizations like Instacart to optimize operations, drive sustainable growth, and create exceptional customer experiences in an increasingly data-driven marketplace.
```

