Customer Churn Analysis (SQL)
Business Context
Customer retention is critical for subscription‑based and service‑driven businesses. Understanding why customers leave enables companies to reduce churn, improve customer experience, and protect recurring revenue.
Problem Statement
Analyze customer data to identify key drivers of churn and provide actionable recommendations to improve retention and reduce revenue loss.
Dataset Overview
- ~5,000 customer records
- Customer demographics
- Tenure and contract type
- Service usage metrics
- Support interaction history
- Monthly charges and total charges
- Churn indicator (Yes/No)
Tools Used
- SQL Server
- T‑SQL (Joins, CTEs, Aggregations, Window Functions)
- Python (Pandas) for cleaning and feature engineering
- Excel for summary validation
Methodology
- Data Loading & Exploration
- Inspected dataset shape and structure
- Validated column types and missing values
- Data Cleaning (Python)
- Converted numeric fields (e.g., TotalCharges)
- Filled missing values using median/mode strategies
- Standardized categorical values
- Removed duplicates and invalid entries
- Feature Engineering
- Created Tenure Groups
- Created Monthly Charge Bands
- Generated ChurnFlag (0/1) for SQL analysis
- SQL Analysis
- Segmented churn by tenure group
- Segmented churn by monthly charges
- Segmented churn by contract type
- Calculated churn rates using aggregations and window functions
- Insight Synthesis
- Compared churn patterns across customer segments
- Identified high‑risk groups
Key Insights
- Short‑tenure customers had the highest churn rates.
- Month‑to‑month contracts showed significantly higher churn than long‑term contracts.
- High support interaction + low service usage strongly correlated with churn.
- Higher monthly charges were associated with increased churn likelihood.
Business Recommendations
- Introduce loyalty incentives for early‑tenure customers.
- Promote discounted annual or two‑year contracts.
- Improve support response times and reduce wait durations.
- Launch proactive engagement campaigns for low‑usage customers.

