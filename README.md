# swiggy-sales-customer-analysis
Raw and messy data Cleaning using Power Query and Data Automation followed by Data analysis using pivot tables to extract actionable insights and built an interactive Dashboard.

# Swiggy Sales & Customer Analysis

## Project Overview

This project analyses Swiggy order data using Microsoft Excel to explore sales performance, customer feedback, discount patterns, location-level performance, and monthly sales trends.

The project follows a business-analysis workflow, from data cleaning and organisation in Power Query to PivotTable analysis, visualisation, and actionable recommendations.

## Tools & Skills

- Microsoft Excel
- Power Query for data cleaning and transformation
- PivotTables and PivotCharts
- Dashboard design and interactive filters
- Business analysis and data interpretation
- Data-quality assessment and documentation
- Data Automation

## Business Questions

1. Which products contribute the most to recorded sales?
2. How do new and returning customers differ in sales contribution and feedback?
3. How do feedback patterns compare between discounted and non-discounted records?
4. Which locations contribute the most to sales, and where is average feedback more prevalent?
5. How does recorded sales value change across the available months?

## Key Findings

- **Product performance:** The seven products occupying the top five rank positions account for approximately 42.08% of recorded sales, including ties in the rankings.
- **Customer contribution:** New customers contribute 50.10% of recorded sales, while returning customers contribute 49.90%.
- **Customer feedback:** Returning-customer records show a more favourable feedback distribution, with a lower share of Average feedback and higher shares of Good and Excellent feedback.
- **Discount analysis:** The share of Average feedback is similar for discounted and non-discounted records. The data does not establish whether discounts cause changes in customer feedback.
- **Location performance:** Noida Sector 18 has the highest recorded sales value among the locations analysed. Vaishali is also worth further investigation because of its sales contribution and Average-feedback pattern.
- **Sales trend:** Recorded sales in the analysed trend increase from April to May before declining in June. June data covers only part of the month, so the decline should not be interpreted as a full-month comparison.

## Dashboard

The interactive Excel dashboard brings together product performance, customer sales contribution, discount-related feedback, location performance, and monthly sales trends.

See the dashboard image in the [here](https://github.com/dikshitajena/swiggy-sales-customer-analysis/blob/main/DASHBOARD.png).

## Data Quality & Limitations

- The source data contains repeated `SW216` order IDs associated with differing record details on 14 April 2025. The original records have been retained rather than assigning unverified replacement IDs.
- The sales-trend analysis excludes 14 April because of the unusual recorded activity and order-ID issue. This exclusion applies only to the trend analysis; the records remain in the dataset and other analyses.
- Total recorded sales include the retained records. Sales totals from the trend analysis therefore have a different scope.
- Order-ID counts should not be treated as verified unique-order counts while the ID issue remains unresolved.
- Feedback patterns show associations, not proof of causation. Profitability, discount effectiveness, and customer retention cannot be established from the available fields alone.
- The dataset covers a limited period, and June data is incomplete.

## Recommendations

- Monitor leading products and ensure their availability, while evaluating profitability using cost and margin data if available.
- Investigate the difference in feedback distributions between new and returning customers.
- Evaluate discount strategies using additional information such as margins, order value, and repeat-purchase behaviour.
- Review locations with relatively high Average-feedback counts or shares to identify possible service-improvement opportunities.
- Validate the order-ID anomaly and analyse a longer time period before drawing firm conclusions about sales trends.

## Deliverable

An Excel workbook containing the cleaned data, PivotTables, visualisations, analysis sheets, documented business findings, and an interactive dashboard.

*This is a portfolio case study using practice data. Findings and recommendations are limited to the fields and period available.*

## Author

DIKSHITA JENA

Aspiring Data/Business Analyst

Advanced Excel | SQL | Power BI | Python
