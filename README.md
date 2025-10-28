<h1>Bank Customer Churn Prediction using Power BI</h1>

<h2>Overview :</h2>

This file is a Power BI dashboard built to identify customers at risk of leaving the bank before they actually churn. The churn logic is analysed completely inside Power BI using Power Query for rule-based transformation and DAX. The report gives proactive visibility into leakages and helps in targeting retention.

<h2>What the report shows :</h2>

- Total Number of Customers
- Overall churn rate status vs Target using Gauge chart
- Total Customers by Credit card status
- Total Customers by Churn status
- Total Customers and Churn rate by A/c balance
- Total Customers and Churn rate by Credit Score group
- Total Customers and Churn rate by Age group
- Churn risk segmentation
- Active customer status and relation to other prospects
- Credit Score status and relation to different age groups
- Drill-through to individual customer journeys

<h2>The Final Dashboard report :</h2>

![Final Dashboard](https://github.com/Saikat-Dass/Bank_customers_churn_prediction_report_in_PowerBI/blob/5cd473c5807ef79257c0b79850d70366550bcac4/Final%20Dashboard.png)

<h2>Tools applied :</h2>

- Power BI Desktop — data shaping, rule-logic, DAX modelling, final dashboard
- Power Query — behavioural rules and feature engineering
- DAX — dynamic churn-risk scoring & segmentation
- MS CSV — raw customer data

<h2>Insights</h2>

- Credit Card Status: A substantial majority of customers (70.55%) do not have a credit card with the bank, while 29.45% do.
- Geographic Distribution: The customer base is almost evenly split between France (25.09%), Germany (24.77%), and Spain (50.14%), with Spain having the largest share.
- Active Status: The customer base is almost evenly split between active (48.5%) and inactive (51.5%) customers.
- Account Balance: Churn rate is higher for customers with lower account balances (OK to 10K) and those with very high balances (>200K). The lowest churn rate is observed in the middle balance ranges (10K-200K).
- Credit Score: The churn rate is highest for customers with the lowest credit scores (<400) and for those with scores between 701 and 800.
-Age Group: Churn rate appears to be highest among the older age groups, specifically 51-60 and >71, and lowest for the youngest age group (<20). However, the largest number of total customers are in the 31-40 age group.

<h2>Conclusion :</h2>

The churn patterns reveal that dissatisfied long-tenure customers and single-product customers form the highest exit-risk cohort. Banking retention should not rely on reactions after customers leave — the dashboard proves that churn can be predicted through behavior signals and intercepted before revenue loss.
