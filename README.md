Customer Shopping Behavior Analysis

This project analyzes 3,900 retail transactions across 18 features to understand spending patterns, customer segments, product preferences, and subscription behavior. The goal is to turn raw transactional data into insights that support strategic business decisions.

Workflow

Data cleaning and EDA (Python): Explored the data with pandas, imputed 37 missing Review Rating values using the median rating per product category, standardized column names to snake case, and engineered new features (age_group, purchase_frequency_days). Dropped the redundant promo_code_used column after a consistency check.
SQL analysis (PostgreSQL): Loaded the cleaned data into PostgreSQL and answered seven business questions, including revenue by gender and age group, high-spending discount users, top-rated products, shipping type comparison, subscribers vs. non-subscribers, and the link between repeat buying and subscriptions.
Dashboard (Power BI): Built an interactive Customer Behavior Dashboard with KPIs (3.9K customers, $59.76 average purchase, 3.75 average rating) and filters for subscription status, gender, category, and shipping type.

Key Insights

Male customers generated about 2x the revenue of female customers (157,890 vs. 75,191).
Subscribers make up only 27% of customers, yet their average spend is nearly the same as non-subscribers (59.49 vs. 59.87), so subscriptions are underused rather than unprofitable.
Young Adults contribute the highest revenue among age groups.
Express shipping users spend slightly more per order than Standard (60.48 vs. 58.46).
Many repeat buyers (2,518) are still not subscribed, which suggests a clear opportunity for conversion.

Business Recommendations: Promote subscriber benefits, launch loyalty programs for repeat buyers, review discount policy to protect margins, feature top-rated products in campaigns, and target high-revenue age groups and express-shipping users.
