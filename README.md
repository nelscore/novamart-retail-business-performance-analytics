# NovaMart Retail Business Performance Analytics

An end-to-end retail business performance analytics case study built with Microsoft Excel, focused on transforming transactional retail data into reliable KPIs, business insights, and management recommendations.

> **Portfolio Case Study:** NovaMart Retail is a fictional business scenario created for analytical and portfolio demonstration purposes.

## Business Problem

Retail management needs a clear view of sales performance, profitability, product and category contribution, customer behavior, regional performance, and discount economics.

This project transforms retail transaction data into a structured decision-support view for management, evaluating revenue growth alongside profitability, concentration, customer and product contribution, regional differences, and discount-related economics.

## Objectives

- Establish a reliable data-quality and cleaning workflow.
- Develop a consistent KPI layer for business reporting.
- Analyze sales and profit performance over time.
- Identify important product, category, subcategory, customer, and regional patterns.
- Evaluate discount bands and their relationship with profitability.
- Apply Pareto analysis to understand revenue concentration.
- Translate analytical findings into actionable business recommendations.
- Validate analytical outputs before presenting business conclusions.

## Data Source

The project uses Tableau's **Sample Superstore — Superstore Sales** dataset as the underlying source data.

Tableau provides Superstore as sample data representing a fictitious retail company.

**Official Source:**  
https://public.tableau.com/app/resources/sample-data

The original source dataset is not redistributed in this public repository. Reproduction should begin by obtaining the dataset directly from the official Tableau source.

## Tools & Technologies

- **Microsoft Excel** — data cleaning, validation, calculations, pivot tables, KPI analysis, and dashboarding
- **CSV** — structured analytical outputs
- **GitHub** — project versioning, documentation, and portfolio presentation

## Key KPIs

The project defines and validates KPIs including:

- Total Revenue
- Total Profit
- Profit Margin %
- Orders
- Units Sold
- Customers
- Average Order Value (AOV)
- Average Discount
- Repeat Purchase Rate
- Revenue per Customer
- YoY Revenue Growth
- YoY Profit Growth
- Product Margin %
- Revenue Contribution %
- Cumulative Revenue % for Pareto analysis

## Analysis Performed

### Executive & Growth Analysis

- Revenue, profit, orders, units, customers, margin, and AOV
- Year-over-year revenue, profit, order, and customer growth
- Monthly performance trends

### Product & Category Analysis

- Product-level revenue and profitability
- Category and subcategory performance
- Revenue contribution and margin comparison
- Loss-making product identification
- Product Pareto concentration analysis

### Customer Analysis

- Customer revenue and profitability patterns
- Customer contribution and concentration
- Customer Pareto analysis
- Repeat-purchase metrics

### Regional Analysis

- Regional revenue and profitability comparison
- Regional margin differences
- Identification of high-scale and weaker-margin regions

### Discount Analysis

- Revenue, profit, orders, units, and margin by discount band
- Comparison of profitability across discount levels
- Descriptive assessment of discount economics

### Returns Analysis

Return analysis was considered in the project scope. However, the supplied source dataset does not contain return fields.

Therefore, return KPIs are **not fabricated** and are not presented as calculated results.

## Key Business Insights

Based on the validated analytical outputs:

- Approximately **$2.30M revenue** was generated across **5,009 orders and 793 customers**.
- Overall profit is approximately **$286.4K at a 12.47% margin**.
- **Technology** is the leading revenue category, contributing approximately **36.4% of total revenue**.
- **Technology** also leads total profit.
- **Furniture** has the weakest category margin at approximately **2.5%**, indicating potential margin pressure.
- The **West** region leads revenue, while **Central** has the weakest reported regional margin.
- The top 20 products contribute approximately **16.9% of revenue**, showing meaningful product concentration.
- The top 20 customers contribute approximately **11.5% of revenue**, indicating measurable customer concentration.
- **306 of 1,894 products** are loss-making in aggregate, highlighting the need for product-level economic review.
- The **0% discount band** has the highest observed profit and margin in the supplied analysis. This is a descriptive association and does not establish causal impact.

## Business Recommendations

- Prioritize profitable growth rather than revenue growth alone.
- Protect availability and economics of high-contribution Technology products.
- Review Furniture product mix, pricing, discounting, and fulfillment economics.
- Investigate regional mix and discount patterns in weaker-margin areas.
- Monitor high-contribution products and customers to manage concentration risk.
- Review loss-making products for pricing, discount, and fulfillment economics.
- Use controlled tests before concluding that a specific discount level causes better profitability.
- Integrate actual returns data in a production environment before making return-related decisions.

## Dashboard Preview

The project includes an Excel-based dashboard covering:

- Executive KPIs
- Sales Performance
- Product Performance
- Customer Analysis
- Profitability & Discount Analysis
- Regional Performance
- Business Insights

Dashboard screenshots are maintained in:

`07_Portfolio/dashboard_screenshots/`

## Repository Structure

```text
01_Project_Control/     Project purpose, workflow, and analytical principles
02_Data/                Data documentation, source information, and datasets
03_Analysis/            Validated analytical outputs and advanced analysis
04_Excel_Dashboard/     Final Excel dashboard workbook
05_Documentation/       Data dictionary, QA, KPI definitions, and documentation
06_Insights/            Business insights and recommendations
07_Portfolio/           Portfolio-ready summaries, case study, and dashboard materials
