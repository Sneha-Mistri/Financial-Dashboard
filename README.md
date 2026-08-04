# ⚡ FinSight: Finance Analytics Dashboard
A dynamic, interactive Power BI dashboard built for a financial organization to monitor transaction performance, track revenue drivers, analyze customer demographics, and measure risk metrics across regional markets.

1. Project Title / Headline
💳 FinSight: End-to-End Financial Analytics & Customer Insights Dashboard

A dynamic Power BI reporting solution designed to track transaction volumes, operational fees, tax collections, customer segment performance, and YoY growth metrics across multi-state operations.

2. Short Description / Purpose
The FinSight Analytics Dashboard offers a centralized solution for finance leaders, risk analysts, and operations teams. Built with a two-tab navigation system (Overview Analysis and Transactions), it combines high-level executive KPI tracking with a granular record-level grid for audit, reconciliation, and deep-dive analysis.

3. Tech Stack
Power BI Desktop – Interactive report design, dashboard wireframing, and visual formatting
Power Query – Data cleaning, schema transformation, type formatting, and source path mapping
DAX (Data Analysis Expressions) – Calculated measures, Time Intelligence formulas (YoY Amount, YoY Transactions), dynamic metric selection logic, and KPI aggregations
Data Modeling – Established Star Schema connecting finance_transactions fact table with customers and calendar dimension tables
File Format – .pbix (Full Report & Data Model) & .pbit (Report Template)

3. Dashboard Structure & Features
📌 Page 1: Overview Analysis (Executive Insights)
Primary KPIs (Header Bar)
Total Amount: Total transaction monetary value processed + YoY growth comparison.
Total Transactions: Total count of transactions executed with yearly volume changes.
Average Transaction Value: Average revenue generated per processed transaction.
Total Fees: Aggregate operational fees collected from processing.
Total Tax: Total tax revenue generated across all transactions.

Visual Analytics Breakdown
📉 Total Amount by Month (Line/Area Chart): Evaluates monthly transaction trends to spot seasonal spikes or operational drops.
⭕ Total Amount by Transaction Status (Donut Chart): Compares Success, Failed, and Pending transactions to monitor system health.
📊 Total Amount by Customer Segment (Bar Chart): Measures revenue contributions across Retail, Premium, SME, Corporate, and Wealth clients.
📍 Total Amount by State (Bar Chart): Ranks financial performance by region to pinpoint high-value markets.
📋 Transaction Type Matrix (Heatmap Table): Matrix displaying Amount, Fees, Tax, and Count across 10 transaction types (Bill Payment, Card Payment, Deposit, Fee Charge, Interest Credit, Investment, Loan EMI, Refund, Transfer, Withdrawal).
👥 Total Amount by Gender (Donut Chart): Tracks customer demographic distribution (Male vs. Female).
📌 Page 2: Transactions (Detailed Grid & Drill-Down)
📄 Underlying Records Grid: Detailed table displaying line-by-line raw transaction data for audit and reconciliation.
🔍 Interactive Drill-Through: Allows users to filter down to specific transaction IDs, customer details, occupations, and category filters selected on the Overview tab.

5. Business Impact & Insights Summary
By centralizing transaction data, risk teams can immediately identify high failure rates across specific payment channels or regions to prevent revenue leakage. Operations leadership can leverage state-wise and customer segment breakdowns (Corporate vs. Retail) to allocate resources toward high-margin customer bases. Additionally, tracking Fees and Tax alongside base transaction amounts equips finance strategists to optimize pricing structures, forecast tax liabilities, and drive overall organizational profitability.

# Snapshot - Overview
![Dashboard Preview](https://github.com/Sneha-Mistri/Financial-Dashboard/blob/main/Financial_Overview_Snapshot.png)

# Snapshot - Transaction
![Dashboard Preview](https://github.com/Sneha-Mistri/Financial-Dashboard/blob/main/Financial_Transaction_Snapshot.png)
