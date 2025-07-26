# Teelcom--churn
This report analyzes customer churn behavior using a telecom dataset. Visual analytics and statistical breakdowns were used to uncover churn patterns across demographics, service features, contract types, and payment behaviors

📊 Executive Summary: Telecom Customer Churn Analysis
This report analyzes customer churn behavior using a telecom dataset. Visual analytics and statistical breakdowns were used to uncover churn patterns across demographics, service features, contract types, and payment behaviors. The goal is to identify actionable strategies to improve retention.

🔍 Key Insights with Detailed Analysis:
1. Churn Rate Overview
Overall churn rate in the dataset is approximately 26.5%, meaning over 1 in 4 customers have left the service.

This highlights a critical retention issue and demands targeted interventions.

2. Demographic Influence on Churn
Senior Citizens:

Represent 16% of total customers.

Among them, 42% have churned — significantly higher than the 24% churn rate among non-senior citizens.

🔎 Insight: Older users may struggle with tech adoption or perceive less value.

Gender:

Churn rates are fairly balanced between males (26.4%) and females (26.8%).

🔎 Insight: Gender does not appear to be a strong indicator of churn behavior.

Dependents & Partners:

Customers with no dependents show a 31% churn rate vs only 15% for those with dependents.

Similarly, customers without partners have nearly double the churn rate compared to those with partners (31% vs 16%).

🔎 Insight: Stronger household ties correlate with higher retention.

3. Tenure & Loyalty
Tenure is one of the strongest predictors of churn:

Customers with tenure < 12 months show a churn rate of ~45%.

For tenure > 60 months, churn drops to below 5%.

🔎 Insight: Long-term customers are much more loyal — highlighting the need for better onboarding and early-stage incentives.

4. Contract Types and Churn
Month-to-month contracts: Churn rate = 43%

One-year contracts: Churn rate = 11%

Two-year contracts: Churn rate = 3%

🔎 Insight: Lock-in contracts strongly reduce churn; consider incentives for longer commitments.

5. Services and Their Role in Retention
Customers without services like OnlineSecurity, TechSupport, and OnlineBackup are 30–40% more likely to churn.

For example:

TechSupport subscribers: only 15% churn

No TechSupport: 35% churn

🔎 Insight: Bundling and promoting support/backup services can improve satisfaction and retention.

6. Internet Service Types
Fiber optic users show higher churn (42%) compared to DSL users (19%) or those without internet (7%).

🔎 Insight: Fiber customers might be more price-sensitive or have higher expectations.

7. Payment Method Patterns
Electronic check users churn the most (45%).

Credit card and bank transfer users show much lower churn (15–17%).

🔎 Insight: Manual payments may correlate with disengagement; promote auto-payment options.

📈 Visual Strategy Highlights
The notebook effectively used:

Count plots to show churn split across all major categorical features.

Stacked bar charts with percentages to make comparisons easier.

Tenure binning to demonstrate early vs. long-term customer behavior.


