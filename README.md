## Project Overview
In this project, I analyzed transactional e-commerce data to understand customer purchasing behavior, revenue concentration, and the impact of product returns. My goal was to identify which customers, products, and markets drive the majority of revenue and to surface insights that could inform retention strategies, product focus, and operational decision-making.

## Tools & Technologies
- Python (pandas, NumPy)
- Power BI
- Jupyter Notebook 

## Dataset

The dataset consists of transaction-level online retail data, including customer identifiers, product details, quantities, prices, timestamps, country information, and indicators of cancelled or returned transactions. This level of granularity allowed for detailed analysis of revenue drivers, repeat purchasing behavior, and return patterns.

## Scope & Approach
	I dedicated significant effort to data cleaning and validation to ensure transaction-level accuracy before drawing conclusions. This included filtering cancelled transactions, removing invalid quantities or prices, and resolving inconsistencies that could distort revenue calculations.
During the exploratory phase, I tested and refined multiple investigative questions. The final analysis focuses on the most decision-relevant questions and insights that remained after validating data quality, rather than documenting every intermediate exploratory step.

## Key Business Questions

- How concentrated is revenue across countries and products?
- To what extent do product returns impact overall revenue?
- Are product returns disproportionately driven by a small subset of products?
- Which products contribute the most to revenue relative to their return behavior?

## Key Insights

- Revenue is highly concentrated among a relatively small set of countries and products.
- While product returns occur across the catalog, their impact on overall revenue is primarily driven by a limited number of products.
- Most products contribute positively to revenue with relatively low return behavior, suggesting targeted intervention is more effective than broad operational changes.
- Retention and focus on high-impact products provide greater leverage than optimizing for transaction volume alone.


## Power BI Integration
	I used Power BI to operationalize the insights derived in the analysis by building dashboards that monitor revenue, returns, and product performance. These dashboards enable country- and product-level drilldowns aligned with the concentration patterns identified in the notebook, focusing on insight communication rather than additional data exploration.

## Next Steps
	With the core revenue and return patterns established, I would extend this work by segmenting customers based on purchasing and return behavior, tracking customer lifetime value over time, and automating revenue and return monitoring using SQL-based pipelines feeding dashboards.
