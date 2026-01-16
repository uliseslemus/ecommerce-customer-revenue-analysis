# E-commerce Customer Revenue & Returns Analysis

## Project Overview

This project analyzes transactional e-commerce data to identify the customers, products, and markets that drive the majority of revenue. The analysis focuses on revenue concentration, repeat purchasing behavior, and the impact of product returns, with the goal of surfacing insights that support retention strategies, product prioritization, and operational decision-making.


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

To support interactive exploration and stakeholder-friendly presentation, I developed a Power BI dashboard that summarizes key customer and revenue insights. The dashboard focuses on revenue concentration, repeat versus one-time customer behavior, and the relationship between returns and net revenue.

The report enables users to quickly identify high-impact customers and products, explore country-level performance, and assess how return behavior affects overall profitability.

## Next Steps

Future iterations of this project could expand on the current analysis by incorporating customer-level segmentation, cohort-based retention analysis, and predictive modeling for return likelihood.

Additional enhancements may include automating the data pipeline, enriching the dataset with marketing or acquisition data, and extending the dashboard to support scenario analysis for pricing or inventory decisions.

