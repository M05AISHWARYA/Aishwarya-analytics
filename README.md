# Aishwarya-analytics
CUSTOMER AND TRANSACTION INSIGHTS

This project focuses on analyzing customer behavior, account usage, transaction patterns, and fraud risks using structured data.
The goal of the project is to convert raw data into business insights that can support decision-making.

Tools & Technologies

SQL (MySQL) – Data analysis, joins, KPI calculations

Power BI Desktop – Data modeling, DAX calculations, dashboard design

Excel – Dataset preparation

The project uses three related datasets:

Customers: Customer demographic details (age, gender, region)

Accounts: Account information (account type, balance, status, open date)

Transactions: Transaction records (amount, date, channel, fraud indicator)

Data relationships:

Customers → Accounts → Transactions

1️⃣ Data Preparation

Reviewed datasets for consistency

Verified key columns (Customer ID, Account ID)

Ensured proper data types for dates and numeric fields

2️⃣ SQL Analysis

Using SQL queries, I:

Calculated total customers, accounts, and transactions

Analyzed customer age groups and gender distribution

Identified most-used account types

Analyzed transaction volume by channel

Calculated fraud transaction count, amount, and percentage

Performed joins across multiple tables for deeper analysis

3️⃣ Power BI Data Modeling

Imported all tables into Power BI

Created manual relationships between tables

Used one-to-many relationships for accurate filtering

Validated model before creating visuals

4️⃣ Power BI Calculations

Created KPI measures using DAX

Used measures instead of calculated columns

Built customer age groups and segmentation

Calculated fraud-related KPIs

📈 Key Insights

Majority of customers fall in the 25–35 age group

Savings accounts are the most commonly used account type

Digital payment channels contribute to the highest transaction volume

Fraud occurrences are higher in online channels

Certain account types show higher fraud risk

Transaction trends highlight specific periods with higher activity

Key Insights

Customers aged 36–50 and 50+ represent the largest user base, indicating higher financial engagement among middle-aged and senior customers.

Debit and Credit accounts are almost equally used, showing balanced adoption across account types.

Online and Branch channels generate the highest transaction volumes compared to ATM transactions.

The overall fraud rate (~5%) is notable, with Credit transactions showing slightly higher fraud exposure than Debit.

Fraud occurrences are more frequent in Online and Branch channels, highlighting channel-specific risk areas.

🎯 Business Impact
Develop a fraud risk scoring model based on transaction behavior and historical patterns.

Perform customer segmentation using transaction frequency and value to identify high-value customers.

Add time-based fraud analysis (hourly/daily trends) to detect peak risk periods.

Implement drill-through dashboards for customer-level and transaction-level investigation.

Integrate real-time or near real-time data for proactive fraud monitoring and alerts.

This dashboard helps:

Understand customer behavior

Identify high-risk transaction channels

Monitor fraud trends

Support data-driven business decisions
