# Telco Customer Churn Analysis

This project analyzes customer churn data from a telecommunication company to identify patterns and predict which customers are likely to cancel their service. The goal is to support retention strategy with actionable insights and predictive modeling.

**Tools:** Python, Pandas, Seaborn, scikit-learn, SQL, Tableau

**Dataset:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (from Kaggle)

## Key Objectives
- Clean and preprocess customer churn data.
- Explore trends across contract types, tenure, and billing behavior.
- Visualizae churn rates, customer tenure, and payment method patterns.
- Build a Tableau dashboard to support retention strategies

## Tableau Dashboard 

Includes:
- KPI cards for churn rate, average tenure, and monthly charges
- Churn breakdown by contract type 
- Monthly charges distribution by churn status 
- Customer tenure histogram
- Churn rate over time

[View Dashboard on Tableau Public](https://public.tableau.com/views/Telco_Customer_Churn_Analysis/TelcoChurnAnalysis-KeyInsightsDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Key Findings 

- Month-to-month contracts show significantly higher churn rates.
- Customers with longer tenure are less likely to churn.
- Higher monthly charges are associated with increased churn likelihood.
- Churn varies widely across payment methods and services.

## Business Recommendations

- **Target Month-to-Month Customers:** Focus retention efforts on customers with month-to-month contracts, as they are more likely to churn.
- **Reduce Monthly Charges for High-Risk Segments:** Offer discounts or bundling incentives for customers with high monthly charges who show signs of churn.
- **Improve Support Services:** Customers with no tech support or security services tend to churn more. Encourage adoption of these services through upselling or free trials.
- **Reward Loyalty:** Offer benefits for tenure milestones to retain long-term customers and reduce churn in early months.

