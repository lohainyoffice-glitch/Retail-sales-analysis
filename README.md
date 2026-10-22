# Retail Sales Analysis | 2024–2025

## Project Overview

This project explores retail sales data from 2024 to 2025 to identify revenue trends, compare product categories and sales channels, understand customer segments, and examine the relationship between discounts and sales performance.

The goal is to transform raw transactional data into actionable business insights through data cleaning, exploratory data analysis (EDA), and interactive visualization using Tableau.

## Business Objectives

- Analyze monthly revenue trends and year-over-year performance.
- Identify the highest- and lowest-performing product categories.
- Compare revenue across sales channels and geographic regions.
- Evaluate revenue distribution across customer segments.
- Investigate sales performance across different discount levels.
- Identify the top 10 and bottom 5 products by revenue.

## Dataset

- **Source:** Retail sales dataset used for this portfolio project.
- **Period:** January 2024 – December 2025.
- **Records:** 120,000 transactions.
- **Columns:** 17 fields.

Key variables include:

- `transaction_date`
- `transaction_id`
- `sales_amount`
- `quantity`
- `unit_price`
- `discount_pct`
- `category`
- `customer_segment`
- `sales_channel`
- `region`
- `product_name`

## Tools & Technologies

- **Python:** Data cleaning and exploratory data analysis.
- **Pandas & NumPy:** Data manipulation and analysis.
- **Matplotlib & Plotly:** Data visualization.
- **Jupyter Notebook:** Analysis workflow and documentation.
- **Tableau Public:** Interactive dashboard development.
- **Git & GitHub:** Version control and project portfolio.

## Project Workflow

1. **Data Understanding:** Reviewed the dataset structure, variables, and data quality.
2. **Data Preparation:** Prepared a clean dataset for analysis.
3. **Exploratory Data Analysis:** Investigated revenue, product categories, customer segments, sales channels, regions, and discounts.
4. **Business Insights:** Summarized key findings and potential business implications.
5. **Dashboard Development:** Created visualizations in Tableau to communicate the results.

## Key Findings

### Overall Performance

- **Total revenue:** €45,357,054.45
- **Total transactions:** 120,000
- **Average transaction value:** €377.98

### Revenue Trends

Total revenue was approximately €22.79 million in 2024 and €22.57 million in 2025, representing a decrease of approximately 0.95%. The results suggest relatively stable annual revenue, without sustained growth across the two years.

### Product Categories

- **Highest revenue:** Beauty — €6.36 million.
- **Lowest revenue:** Clothing — €4.63 million.

Revenue was distributed across several categories, with differences in performance between the highest- and lowest-performing categories.

### Sales Channels

In-Store generated approximately €15.27 million, followed by Mobile App at €15.07 million and Online at €15.02 million. Revenue was relatively balanced across the three channels.

### Customer Segments

Revenue was distributed relatively evenly across Loyal, New, VIP, and Returning customers. No single segment dominated overall revenue.

### Discounts

Approximately 40% of transactions included a discount. Average transaction value was lower among discounted transactions than among transactions without discounts. This is a descriptive association and does not establish that discounts caused the difference.

### Product Performance

Bread and Lipstick were the highest-revenue products, generating approximately €2.07 million and €2.06 million, respectively. The analysis also identified the five lowest-revenue products to highlight areas for further investigation.

## Tableau Dashboard

**Interactive dashboard:** [View the Retail Sales Performance Dashboard](https://public.tableau.com/views/RetailSalesPerformanceDashboard_17924510324240/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

The dashboard includes:

- Monthly Revenue Trend (2024–2025)
- Revenue by Product Category
- Revenue by Sales Channel
- Revenue by Region
- Revenue by Customer Segment
- Total Revenue by Discount Level
- Top 10 Products by Revenue
- Bottom 5 Products by Revenue
- KPI indicators for total revenue, transaction count, and average transaction value

A category filter is included to support interactive exploration of product performance.

## Repository Structure

```text
Retail-sales-analysis/
├── 01_data_understanding.ipynb
├── 02_eda.ipynb
├── retail_sales_dataset.csv
├── retail_sales_clean.csv
└── README.md
```

*Note: The file list above reflects the expected project structure. Adjust the names if your repository uses a different structure.*

## Business Recommendations

Based on the exploratory findings:

- Investigate the factors behind the slight decrease in annual revenue from 2024 to 2025.
- Explore why Beauty performs strongly and whether its successful practices can be applied to other categories.
- Review the performance of lower-revenue products before making assortment or inventory decisions.
- Evaluate discount strategies using profitability and margin data, not revenue alone.
- Continue monitoring sales channels and customer segments to identify more specific opportunities for growth.

These recommendations are starting points for further analysis; additional information, such as profit margins, inventory levels, and customer purchase history, would be needed to validate them.

## Limitations

- The analysis is descriptive and does not establish causal relationships.
- Revenue alone does not measure profitability.
- The dataset may not include all variables needed to explain changes in customer behavior or sales performance.
- Findings apply to the dataset and period analyzed.

## Author

**Lohainy Cristina Santos Silva**

Data Analyst | Retail Analytics | Python | SQL | Tableau

This project is part of my data analytics portfolio, demonstrating my ability to explore datasets, analyze business performance, communicate insights, and build data visualizations.

[Connect with me on LinkedIn](ADD_YOUR_LINKEDIN_PROFILE_HERE)
