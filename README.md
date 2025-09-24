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
v.	Complaint Frequency
vi.	Engagement Index
vii.	Senior Flag
5.	Data Integration – Merged five datasets (telco_customer_demographics.csv, telco_billing_payments.csv, telco_usage_subscriptions.csv, telco_support_complaints.csv, telco_churn_labels.csv) into a single dataset using Customer ID as the key.
6.	Exploratory Data Analysis (EDA) – Visualized churn distribution and top churn reasons.
##  Repository Contents
1. 	telco_customer_demographics.csv – Demographic data
2.	telco_billing_payments.csv – Billing and payment data
3.	telco_usage_subscriptions.csv – Usage and subscription details
4.	telco_support_complaints.csv – Customer support and complaints
5.	telco_churn_labels.csv – Churn outcome labels
6.	telco_integrated_dataset.csv – Final cleaned and feature-engineered dataset
7.	CHURN Project-Ready Dataset.ipynb – Jupyter Notebook with data integration, cleaning, feature engineering, and EDA
8.	Churn_Prediction_Data_Collection_Presentation.pptx – PowerPoint presentation of the milestone project
## Tools & Technologies
1.	Python (Pandas, NumPy, Seaborn, Matplotlib)
2.	Jupyter Notebook
3.	GitHub for version control
4.	PowerPoint for presentation deliverables


