# CHURN-PREDICTION-DATASET
This project prepares and analyzes telecom customer data for churn prediction. Using demographics, billing, usage, support, and churn label datasets. I cleaned, transformed, integrated, and engineered features to build a reliable dataset. EDA highlights churn distribution and reasons. 
##  Project Overview
Customer churn is a major challenge in the telecom industry. A major telecoms company in Nigeria faced a dramatic drop in subscribers, highlighting the need for advanced analytics to identify at-risk customers and implement proactive retention strategies.
This project prepares a high-quality dataset that serves as the foundation for predictive modeling. The steps documented here ensure data integrity, consistency, and ethical handling before applying machine learning techniques.
##  Key Steps in the Project
1.	Data Collection – Extracted from multiple sources (CRM, Billing, OSS/BSS, Support Logs, Churn Labels).
2.	Data Cleaning – Removed duplicates, handled missing values, standardized formats, and detected outliers.
3.	Data Transformation – Encoded categorical values, normalized numerical features, and prepared variables for modeling.
4.	Feature Engineering – Created new features such as:
i.	ARPU (Average Revenue per User)
ii.	Payment Consistency
iv.	Service Bundling Score
o	Complaint Frequency
o	Engagement Index
o	Senior Flag
5.	Data Integration – Merged five datasets (telco_customer_demographics.csv, telco_billing_payments.csv, telco_usage_subscriptions.csv, telco_support_complaints.csv, telco_churn_labels.csv) into a single dataset using Customer ID as the key.
6.	Exploratory Data Analysis (EDA) – Visualized churn distribution and top churn reasons.
##  Repository Contents
•	telco_customer_demographics.csv – Demographic data
•	telco_billing_payments.csv – Billing and payment data
•	telco_usage_subscriptions.csv – Usage and subscription details
•	telco_support_complaints.csv – Customer support and complaints
•	telco_churn_labels.csv – Churn outcome labels
•	telco_integrated_dataset.csv – Final cleaned and feature-engineered dataset
•	CHURN Project-Ready Dataset.ipynb – Jupyter Notebook with data integration, cleaning, feature engineering, and EDA
•	Churn_Prediction_Data_Collection_Presentation.pptx – PowerPoint presentation of the milestone project
## Tools & Technologies
•	Python (Pandas, NumPy, Seaborn, Matplotlib)
•	Jupyter Notebook
•	GitHub for version control
•	PowerPoint for presentation deliverables


