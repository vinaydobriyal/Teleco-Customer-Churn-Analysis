# Telecom Customer Churn Analysis 📉

**Project Goal:** To identify the primary drivers of customer attrition within a telecommunications dataset and provide actionable, data-driven retention strategies.

This repository contains a comprehensive Exploratory Data Analysis (EDA) focused on understanding customer behavior, contract preferences, and payment friction points that lead to churn. 

**Tech Stack**
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Plotly, Seaborn, Matplotlib

**Key Analytical Insights**
* **Contract Vulnerability:** Month-to-month subscribers exhibit the highest churn rate by a significant margin due to the lack of exit friction.
* **Service Tier Discrepancies:** Fiber Optic internet customers churn at a disproportionately higher rate than DSL users, indicating potential service reliability or pricing issues.
* **Payment Method Friction:** Customers paying via manual methods like "Electronic Check" are far more likely to churn compared to those using automated payments (Credit Card/Bank Transfer).
* **Early-Stage Attrition:** Density distributions reveal a massive spike in churn during the first few months of tenure. Customers who survive the initial 6-month onboarding window show exponentially higher long-term retention.

**Strategic Recommendations**
1. Incentivize 1-year and 2-year contracts with targeted discounts to stabilize Monthly Recurring Revenue (MRR).
2. Push automated payment adoption by offering small recurring discounts or one-time bill credits to reduce billing friction.
3. Implement a proactive 90-day onboarding sequence, especially for Fiber Optic customers, to build loyalty during the most vulnerable tenure phase.

**Repository Structure**
* `data/`: Contains the raw Telco customer dataset (CSV).
* `notebooks/`: Jupyter notebook containing the complete data cleaning, feature engineering, and visualization code.
* `reports/`: The finalized strategic business presentation for stakeholders.

**How to Run**
1. Clone this repository.
2. Install required dependencies: `pip install pandas numpy plotly seaborn matplotlib`
3. Run `Teleco_Customer_Churn.ipynb` in your preferred Jupyter environment.
