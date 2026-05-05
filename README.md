**Customer Churn Analysis Dashboard (SQL + Power BI)**
<img width="623" height="351" alt="image" src="https://github.com/user-attachments/assets/5d8d5128-e125-46d2-a6fd-d670b59a5c64" />
<img width="632" height="352" alt="image" src="https://github.com/user-attachments/assets/9cd6e06a-3c88-4728-85ad-ea39f25f2bee" />


**Project Overview**
Customer churn has a significant impact on recurring revenue and long‑term business growth.
This project analyzes customer churn data to identify who is churning, why they are leaving, and which factors most strongly influence churn, using SQL for data preparation and Power BI for analysis and visualization.
The goal of this project is to transform raw customer data into actionable insights that help business stakeholders design effective retention strategies.

**Problem Statement**
Businesses often struggle to understand the root causes of customer churn.
This project aims to:

**Measure overall churn and retention performance**
Identify high‑risk customer segments
Analyze churn drivers such as pricing, tenure, contracts, and service quality
Quantify revenue loss due to churn
Provide data‑driven recommendations to reduce churn


**Tools & Technologies**
SQL Server (SSMS) – Data ingestion, cleaning, modeling, and analysis
Power BI – Data modeling, DAX measures, and dashboard creation
DAX – KPI and churn metric calculations


**Data Preparation & Modeling**
Raw churn data was first loaded into a staging table in SQL Server.
The data was cleaned and normalized into domain‑specific tables:
**Customers
Billing
Services
Support & Add‑ons
Streaming & engagement
**

Missing values were handled during transformation to preserve raw data integrity.
A SQL reporting view was created to act as a semantic layer for Power BI:
Centralized joins
Consistent business logic
Simplified reporting model

This approach ensures data consistency, scalability, and easier maintenance.

**Key Insights**
Overall churn rate is ~27%, indicating a strong need for retention strategies.
Revenue loss due to churn is significant, as churned customers typically have higher‑than‑average monthly charges.
Churn volume is highest among long‑tenured customers, as they represent the largest customer base.
Month‑to‑month contracts show the highest churn risk due to low commitment.
Customers without premium support churn significantly more, highlighting the impact of service quality.
Higher churn in certain value deals is driven by pricing sensitivity and customer concentration, not deal design itself.


**Business Recommendations**
Introduce loyalty and engagement programs for long‑tenured customers.
Encourage long‑term contracts through incentives and discounts.
Reassess pricing for higher‑priced plans to reduce price‑driven churn.
Offer premium support trials to high‑risk customer segments.
Focus proactive retention efforts on customers identified as high‑risk.

**Dashboard Structure**
The Power BI report containes below pages:-
Executive Churn Overview – Business impact and key KPIs
Churn Drivers & Retention Focus – Segment‑level analysis and actionable insights

**Outcome**
This project demonstrates how SQL and Power BI can be combined to move from raw data to decision‑ready insights, helping organizations reduce churn and protect revenue.
