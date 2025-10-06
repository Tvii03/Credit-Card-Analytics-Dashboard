# Credit-Card-Analytics-Dashboard (Power BI)
## 📁 Project Overview:
This repository contains an interactive Power BI Dashboard that provides insights into Credit Card Transactions and Customer Profiles.
It is designed to help financial institutions, analysts, and business teams track key performance metrics, customer demographics, and spending behaviors.

Reports Included:
1. Credit Card Customer Report 
• Revenue by Income Group, Age Group, Education, Job Type, and Marital Status
• Revenue distribution by Dependents and State
• Total Revenue, Income, and Interest Earned

2. Credit Card Transaction Report 
• Quarterly Revenue & Transaction Volume Trends
• Revenue breakdown by Expenditure Type (Bills, Travel, Food, Entertainment, etc.)
• Revenue by Customer Job, Education, and Card Category (Blue, Silver, Gold, Platinum
• Insights into Transaction Modes (Swipe, Chip, Online)
• Key performance metrics: Total Revenue, Interest Earned, Annual Fees, and Acquisition Cost

🚀 Features:
• Comprehensive KPI tracking: Revenue, Transactions, Interest etc.
• Interactive filters for Time Period, Card Type, and Demographics
• Business insights to support marketing, credit risk assessment, and customer targeting

🔹 Data Processing:
DAX Queries used to:
- Calculate Revenue, Interest, WoW Revenue
- Create Income Groups, Age Groups etc.
- Derive KPIs like Customer Spend Score (CSS) and Acquisition Cost

SQL Queries used to:
- Extract and Transform raw transaction and customer data from PostgreSQL
- Filter and clean data, removing redundant or duplicate records before importing into Power BI
- Optimize query performance for reporting

📈 Key Insights:
• High revenue contribution from Businessman and White-collar customers.
• Spending peaks in Bills, Travel, and Grocery categories.
• Majority of revenue generated from Blue Card customers.
• Revenue significantly influenced by Education level and Age group.
• Male customers are contributing more in revenue 31M, female 26M

📈 Project Insights- Week 53 (31st Dec)
• Revenue increased by 28.8%,
• Overall revenue is 57M
• Total interest is 8M
• Total transaction amount is 46M
• Blue & Silver credit card are contributing to 93% of overall transactions
• TX, NY & CA is contributing to 68%
• Overall Activation rate is 57.5%
• Overall Delinquent rate is 6.06%

🛠️ Tools & Technologies Used:
- PostgreSQL (Database for customer & transaction data)
- Power BI Desktop (Dashboard Development & Visualization)
- DAX (Data Analysis Expressions) for custom measures & calculations
- Data Modeling for revenue, transactions etc
