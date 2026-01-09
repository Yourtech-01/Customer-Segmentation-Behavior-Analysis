This project performs customer segmentation and behavioral analysis using real-world retail transaction data.
The goal is to help a business understand customer purchasing behavior, identify high-value and at-risk customers, and support data-driven marketing and retention strategies.
This project demonstrates end-to-end data analysis, from raw data cleaning to business recommendations.

🔹 Business Problem

Retail businesses often have large amounts of transaction data but lack clarity on:

Who their most valuable customers are

Which customers are at risk of churn

How to target customers effectively without wasting marketing budget

Objective:
Segment customers based on purchasing behavior to improve targeting, retention, and profitability.

🔹 Dataset

Online Retail Transaction Dataset (public retail data)

Each row represents a customer purchase transaction

Key attributes include:

Customer ID

Invoice Date

🔹 Methodology
1️⃣ Data Cleaning

Removed missing customer IDs

Excluded cancelled transactions

Filtered negative and zero quantity or price values

Converted date fields to datetime format

2️⃣ Feature Engineering

Created customer-level behavioral metrics:

Total Spend

Purchase Frequency

Recency (days since last purchase)

Total Quantity Purchased

3️⃣ Customer Segmentation

Used rule-based segmentation for interpretability and business usability:

High-Value Customers

Active Customers

At-Risk Customers

Low-Engagement Customers

4️⃣ Exploratory Analysis

Distribution of customer spending

Purchase frequency patterns

Segment-wise revenue contribution

🔹 Key Insights

A small group of customers contributes a large share of total revenue

High sales frequency strongly correlates with customer value

Several customers show high churn risk based on recency

Retention of high-value customers is more profitable than new acquisition

🔹 Business Recommendations

Retain high-value customers through loyalty programs and exclusive offers

Upsell active customers to higher-margin products

Re-engage at-risk customers using targeted promotions

Avoid excessive discounting for low-engagement customers

🔹 Tools & Technologies

Python

Pandas & NumPy

Matplotlib

Exploratory Data Analysis (EDA)

Business Analytics

🔹 Project Deliverables

Customer_Segmentation_Analysis.ipynb – Full analysis notebook

Customer_Segmentation_Report.pdf – Business-friendly summary report

Customer_Segmentation_Output.csv – Final customer segmentation data

🔹 Why This Project Matters

This project demonstrates the ability to:

Translate raw data into business insights

Perform customer analytics and segmentation

Communicate findings clearly to non-technical stakeholders

Support real-world decision-making


Quantity

Unit Price
