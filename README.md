# Demand-analysis
An end-to-end demand analysis project built using Power BI. The dashboard explores demand patterns, pricing effects, discount influence, and seasonal trends to provide actionable business insights and support strategic decision-making


Workflow
1. Data Cleaning & Preprocessing (Python - Google Colab)
Dataset was imported into Google Colab
Missing and inconsistent values were handled
Region column: values equal to 0 were replaced using mode imputation
Date column: split into Year, Month, and Day for better time-based analysis
Irrelevant column (Epidemic) was removed as it was not useful for analysis
Data types were corrected for consistency
Dataset was prepared for further analysis

2.Outlier Detection
Outliers were analyzed in key numerical features, specifically Price and Demand
Both variables were examined using statistical methods and visualizations (boxplots)
The detected outliers were considered valid business values rather than errors
Therefore, no removal or transformation was applied to preserve the real distribution of the data


3. Exploratory Data Analysis (EDA)
Data distribution was analyzed
Relationships between variables were explored
Initial insights and patterns were identified using visualizations

4. Data Visualization (Power BI)
Cleaned dataset was imported into Power BI
An interactive dashboard was created
Key metrics such as demand trends, pricing impact, and seasonality were visualized

Key Insights

* The Groceries category generates the highest demand compared to other categories.
* Promotional campaigns significantly boost demand and account for a large share of total sales.
* There is a negative correlation between price and demand — higher prices lead to lower demand.
* Discounts increase demand initially, but their effectiveness decreases beyond a certain threshold.
* Demand varies across months, indicating possible seasonal trends.
* Total demand (8M) and units sold (7M) are closely aligned, suggesting stable pricing behavior.

⸻

Recommendations

* Prioritize high-demand categories like Groceries for marketing and inventory planning.
* Use promotions strategically, as they have a strong positive impact on demand.
* Optimize pricing strategies to balance profitability and demand.
* Avoid excessive discounting, as it does not proportionally increase demand.
* Further analyze seasonal patterns to improve forecasting and planning.

⸻

Business Value

This dashboard helps stakeholders:

* Understand the key factors influencing demand
* Make data-driven pricing and promotion decisions
* Improve sales performance and planning strategies
