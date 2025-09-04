# E-Commerce User Behavior Analysis

## Project Overview
This end-to-end data analysis project delves into the Online Retail dataset to uncover user purchasing patterns, identify key business metrics, and predict customer churn. The goal was to transform raw data into actionable insights through SQL, Python, and interactive visualization.

## Data Source
[Online Retail II Dataset from Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci) - A transnational dataset containing all transactions occurring between 01/12/2009 and 09/12/2011 for a UK-based online retail.

## Tools Used
- **Google BigQuery:** Data storage and initial SQL exploration and aggregation.
- **SQL:** Wrote complex queries to extract, clean, and prepare data for analysis.
- **Python (Pandas, NumPy, Matplotlib, Scikit-learn):** Performed in-depth data cleaning, exploratory data analysis (EDA), and built a machine learning model for churn prediction.
- **Google Looker Studio:** Built an interactive dashboard to visualize key insights for stakeholders.

## Key Insights
- **Market Concentration:** The United Kingdom was the dominant market, generating £17.8M in revenue and accounting for over 90% of total sales.
- **Customer Retention Challenge:** A significant 50.85% of the customer base was identified as churned. A large portion of customers (analysis showed a high number of one-time purchasers) represent a major drop-off point.
- **Churn Prediction Model:** A Random Forest classifier successfully predicted customer churn with **100% accuracy** on the test set. Feature importance analysis revealed that **Recency** (days since last purchase) was the overwhelming predictor, responsible for **85.7%** of the model's decision, far outweighing Frequency (7.3%) and Monetary value (7.1%).

## Dashboard
[https://lookerstudio.google.com/reporting/3e55ca32-0198-49b3-ae0b-1fe36a4281a2](https://lookerstudio.google.com/reporting/1b69b813-bc33-48b6-845d-e826244fd894)
The dashboard provides an at-a-glance view of key performance indicators (KPIs), including:
- Total Revenue and Customer Count
- Sales distribution by Country
- Sales trends over time
- Customer status (Active vs. Churned)
- Feature importance for the churn prediction model

## Files
- `Ecommerce_Behavior_Analysis.ipynb`: The complete Jupyter notebook containing all Python code for data extraction, cleaning, analysis, and machine learning.
- feature_importance.csv file, churn_counts.csv file.
- `README.md`: This file.
