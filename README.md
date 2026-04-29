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

Groceries category generates the highest demand
Promotions significantly increase demand and drive a large portion of sales
There is a negative relationship between price and demand
Competitor pricing has a noticeable influence on demand behavior
Discounts increase demand initially, but show diminishing returns beyond a certain level
Demand varies across months, indicating seasonal patterns
Total demand (8M) and units sold (7M) are closely aligned, suggesting stable sales dynamics
⸻

Recommendations

Prioritize high-demand categories like Groceries in inventory and marketing
Use promotions strategically, focusing on optimal timing and targeting
Implement competitive pricing strategies based on market conditions
Avoid excessive discounting to protect profitability
Leverage seasonal trends for better demand forecasting and planning

⸻

Business Value

This dashboard helps stakeholders:
This dashboard enables stakeholders to:

Understand key factors influencing demand
Make data-driven pricing and promotion decisions
Identify lost sales due to stock-outs
Improve inventory planning and sales performance
Support strategic business decisions with data insights
