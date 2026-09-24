# Opay-Fintech-Performance-Dashboard
 Page 1 
<img width="890" height="502" alt="Executive Overview" src="https://github.com/user-attachments/assets/a9d5d6e1-2f8f-4f0f-8e31-2dfb2eaf7946" />

Page 2
<img width="891" height="504" alt="Customer   Transaction Analysis" src="https://github.com/user-attachments/assets/87bad1e9-3432-434e-822a-b1be937f64df" />

Page 3
<img width="890" height="508" alt="Risk   Fraud Analysis" src="https://github.com/user-attachments/assets/c6b13be1-6a04-4617-9d5b-4b50ba115cc9" />


## Problem Description
The OPay Fintech Performance Dashboard is an interactive Business Intelligence project developed in Microsoft Power BI to analyse fintech transaction data and provide a comprehensive view of financial performance, customer activity, transaction behaviour, channel performance, transaction outcomes, and fraud-related risk.
The dashboard transforms a large transactional dataset into interactive visual insights that enable users to monitor key performance indicators, compare business performance across different dimensions, identify operational issues, and support data-driven decision-making.
The dashboard consists of three main analytical pages:
1.	Executive Overview – Provides a high-level view of financial and operational performance.
2.	Customer & Transaction Analysis – Examines customer segments, transaction types, channels, transaction volumes, and profitability.
3.	Risk & Fraud Analysis – Focuses on fraudulent transactions, failed transactions, fraud rates, risk categories, and regional fraud patterns.
Interactive slicers allow users to filter the analysis by region, year, transaction type, and customer segment.
## Problem Statement
Fintech platforms generate large volumes of transactional data containing valuable information about financial performance, customers, transaction behaviour, operational reliability, and fraud risk. However, raw transactional data can be difficult to interpret and use effectively for business decision-making.
The project addresses the need for an interactive Business Intelligence solution that converts raw fintech transaction data into meaningful visual insights.
The dashboard was therefore developed to help users:
-	Monitor transaction value, revenue, profit, and transaction volume.
-	Understand transaction performance across different channels and transaction types.
-	Analyze customer segment profitability and activity.
-	Monitor successful, pending, and failed transactions.
-	Identify fraud-related activity and risk patterns.
-	Compare performance across regions and time periods.
-	Provide management with an accessible framework for monitoring business performance and operational risks.
## Project Objectives
The major objectives of the project were to:
-	Develop an interactive Power BI dashboard for monitoring fintech transaction performance.
-	Measure transaction value, transaction volume, revenue, and profit using KPIs.
-	Compare performance across years, channels, transaction types, and customer segments.
-	Examine changes in revenue and profit over time.
-	Analyse the contribution of customer segments and transaction types to profitability.
-	Analyze transaction statuses, including successful, pending, and failed transactions.
-	Assess transaction reliability and potential customer-experience issues.
-	Analyze fraud activity across geographical regions.
-	Examine the distribution of transactions across fraud-risk categories.
-	Provide actionable recommendations for improving profitability, transaction reliability, and fraud management.
-	Present complex transactional data in a concise, interactive, and decision-support format.
## Dashboard Preview
## Tools Used
Microsoft Power BI
Used to:
-	Clean and transform the data.
-	Create calculated measures and KPIs.
-	Build interactive visualizations.
-	Develop dashboard pages.
-	Add slicers and interactive filtering.
-	Analyze financial, customer, transaction, and risk performance.
### Microsoft Excel
Used as the source data format for the transactional dataset.
### Power Query
Used as part of the Power BI data preparation and transformation workflow.
### DAX
Used to create analytical measures and KPIs such as:
-	Total Transaction Value
-	Total Transactions
-	Total Revenue
-	Total Profit
-	Average Transaction Value
-	Fraud Transactions
-	Fraud Rate
-	Failed Transactions
-	Failure Rate
## Dataset Content
The dataset contains:
-	60,000 transaction records
-	46 columns
-	26,030 unique customers
-	Data period: June 2018 – December 2025
The dataset contains information relating to:
-	Transaction identifiers
-	Transaction dates
-	Customer information
-	Geographic/region information
-	Transaction types
-	Transaction channels
-	Transaction status
-	Financial measures
-	Customer value and engagement indicators
-	Fraud-related information
-	Fraud-risk categories
The source data was provided in Microsoft Excel format.
## Dashboard Features
Page 1 – Executive Overview
The Executive Overview provides a high-level summary of business performance.
Features include:
- KPI cards
-	Transaction Value by Year
-	Revenue & Profit by Year
-	Transaction Status analysis
-	Region slicer
-	Year slicer
-	Transaction Type slicer
-	Customer Segment slicer

This page enables users to quickly understand the overall financial and operational position of the business.
Page 2 – Customer & Transaction Analysis
This page focuses on customer and transaction performance.
Features include:
-	Profit by Customer Segment
-	Profit by Transaction Type
-	Transaction Value by Channel
-	Transaction Volume by Channel
-	Customer KPIs
-	Transaction KPIs

It allows users to compare the contribution of different customer segments, transaction types, and channels.
Page 3 – Risk & Fraud Analysis
This page focuses on operational risk and fraud monitoring.
Features include:
-	Fraud Transactions
-	Fraud Rate
-	Failed Transactions
-	Failure Rate
-	Fraud Transactions by Region
-	Fraud Risk Categories
-	Fraud Trends
-	Failed Transactions by Transaction Type

The page provides a dedicated view for monitoring transaction reliability and fraud-related activity.
## Key Findings
### Overall Financial Performance
The analysis recorded:
|KPI |	Result |
|---|---|
| Total Transactions	| 60,000 |
| Unique Customers	  |           26,030 |
| Transaction Value	  |          ₦14.98 Billion |
| Average Transaction Value |     ₦249,676.54 |
| Revenue	                |       ₦9.98 Million |
| Profit	|   ₦5.99 Million |
| Profit-to-Revenue Ratio	|60.02% |
| Fraud Transactions |	19,962 (33.27%) |
| Failed Transactions |	20,130 (33.55%) |
  
### Transaction Status
The dataset showed a relatively balanced distribution of transaction outcomes:
-	Successful: 33.18%
-	Pending: 33.27%
-	Failed: 33.55%

The relatively high proportion of failed and pending transactions highlights transaction reliability as an important area for monitoring.
### Channel Performance
Transaction value was relatively evenly distributed across the four channels:
-	Mobile App: ₦3.80 Billion
-	USSD: ₦3.74 Billion
-	POS: ₦3.74 Billion
-	Agent: ₦3.70 Billion

The channels also showed closely matched transaction volumes and profits.
### Customer Segment Performance
Profitability was also relatively evenly distributed across the four customer segments.

The High Value segment generated the highest profit at approximately ₦1.51 Million, while the Low Value segment generated approximately ₦1.49 Million.

This indicates that customer segments were not strongly differentiated in terms of profitability within this dataset.
### Transaction Type Performance
All seven transaction types generated broadly comparable results.

Bill Payment recorded the highest profit at approximately ₦866,969, while Airtime recorded approximately ₦835,070.

Transaction volume and transaction value were also relatively close across the transaction types.
### Fraud and Risk
The dataset contained:
-	19,962 fraud-flagged transactions
-	33.27% fraud rate
-	20,130 failed transactions
-	Fraud-risk categories of:
o	High: 18,726
o	Medium: 23,969
o	Low: 17,305
Fraud activity was distributed relatively evenly across regions, with fraud rates ranging from approximately 32.98% to 33.49%.
## Recommendations
- Improve Transaction Reliability
Monitor failed and pending transactions across channels, transaction types, and regions to identify their underlying causes and improve transaction completion.
- Strengthen Fraud Management
Enhance fraud detection and prevention processes by monitoring high-risk transactions and investigating suspicious activity across channels and regions.
- Monitor Channel Performance
Track transaction value, transaction volume, and profitability across channels over time to identify changes in channel behaviour.
- Monitor Customer Segments
Use customer-segment analysis to track changes in profitability, transaction activity, and customer behaviour.
- Monitor Transaction Types
Continue monitoring individual transaction types because the dataset does not show one transaction type overwhelmingly dominating performance.
- Use the Dashboard for Decision Support
Use the three-page dashboard structure to move from high-level performance monitoring to detailed customer and transaction analysis and finally to operational risk and fraud monitoring.
## Conclusion
The OPay Fintech Performance Dashboard demonstrates how Microsoft Power BI can transform a large transactional dataset into an interactive Business Intelligence solution.

The dashboard provides an integrated view of financial performance, customer behaviour, transaction activity, channel performance, and fraud risk.

The analysis recorded ₦14.98 billion in transaction value, with relatively balanced performance across channels, customer segments, and transaction types. However, the dataset also showed substantial levels of failed and fraud-flagged transactions, making transaction reliability and fraud management important areas for monitoring.

Overall, the project demonstrates the use of data analytics and Business Intelligence techniques to transform raw fintech data into meaningful insights that can support data-driven operational and management decisions.

## Skills Demonstrated
Technical Skills
-	Microsoft Power BI
-	Power Query
-	DAX
-	Data Cleaning
-	Data Transformation
-	Data Modelling
-	KPI Development
-	Data Visualization
-	Dashboard Development
-	Interactive Report Design
-	Business Intelligence
-	Data Analysis

Analytical Skills
-	Financial Performance Analysis
-	Customer Segmentation Analysis
-	Transaction Analysis
-	Channel Performance Analysis
-	Fraud and Risk Analysis
-	Trend Analysis
-	Comparative Analysis
-	KPI Analysis
-	Business Insights Generation
-	Data-driven Problem Solving

Business Skills
-	Business Performance Monitoring
-	Decision Support
-	Operational Performance Analysis
-	Risk Monitoring
-	Recommendation Development
-	Data Storytelling
-	Executive Reporting
## Project Highlights
- Dataset: 60,000 transactions
- Customers: 26,030 unique customers
- Period: June 2018 – December 2025
- Transaction Value: ₦14.98 Billion
- Revenue: ₦9.98 Million
- Profit: ₦5.99 Million
- Dashboard Pages: 3
- Platform: Microsoft Power BI

Source: Microsoft Excel

Note: *The source dataset is highly balanced across statuses, channels, customer segments, and regions. Therefore, the findings describe the supplied dataset and should not automatically be interpreted as representing actual OPay operational performance. The report also notes that no external verification of the fraud, revenue, or profit figures was performed.*


