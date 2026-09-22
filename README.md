# Finance Analytics Dashboard | Power BI

An interactive Finance Analytics Dashboard developed in Microsoft Power BI to analyze financial transactions, customer behavior, transaction performance, fees, taxes, and regional trends.

## Project Overview

The objective of this project is to provide a centralized analytical solution for monitoring financial transaction performance and understanding customer behavior.

The dashboard helps analyze:

- Transaction trends over time
- Transaction status and performance
- Customer segment contribution
- State-wise transaction performance
- Transaction type analysis
- Fees and taxes
- Gender-wise transaction amount
- Detailed transaction-level records

## Dashboard Pages

### 1. Overview Analysis

The Overview Analysis page provides a high-level view of financial performance through KPIs, charts, and interactive filters.

### 2. Transactions

The Transactions page provides detailed transaction-level records and supports deeper analysis of individual transactions.

## Key KPIs

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax
- Year-over-Year (YoY) comparison

## Interactive Filters

The dashboard includes filters for:

- Year
- Dynamic Metrics
- Occupation
- Merchant Category

## Dashboard Visualizations

- Total Amount by Month
- Total Amount by Transaction Status
- Total Amount by Customer Segment
- Total Amount by State
- Transaction Type Analysis
- Total Amount by Gender
- Detailed transaction table

## Data

The project uses sample financial transaction and customer datasets.

### Customer Data

Contains customer-related information such as:

- Customer ID
- Customer Name
- Date of Birth
- Gender
- Annual Income
- Occupation
- City
- State
- Customer Segment
- Join Date

### Transaction Data

Contains transaction-related information such as:

- Transaction ID
- Transaction Date
- Account ID
- Customer ID
- Transaction Type
- Channel
- Merchant Category
- Amount
- Fee Amount
- Tax Amount
- Currency
- Transaction Status
- Fraud Indicator
- Risk Score
- Reference Number

## Data Preparation

Power Query was used for data cleaning and transformation before building the dashboard.

The data preparation process included:

- Data type validation
- Text cleaning
- Handling missing values
- Column preparation
- Data integration between customer and transaction data

## DAX & Time Intelligence

DAX measures were created for key financial metrics and time-based analysis.

The project includes:

- Total Amount
- Total Fees
- Total Tax
- Total Transactions
- Previous Year Amount
- Year-over-Year analysis
- Dynamic metric selection

## Dynamic Metrics

A Field Parameter was used to allow users to dynamically switch between selected financial measures within the dashboard.

## Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- GitHub

## Repository Structure

```text
finance-analytics-powerbi-dashboard/
│
├── README.md
├── Business Requirements/
├── Data/
├── Power BI/
├── Screenshots/
└── Documentation/
