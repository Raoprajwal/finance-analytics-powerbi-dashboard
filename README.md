# Finance Analytics Dashboard | Power BI

An interactive Finance Analytics Dashboard developed in Microsoft Power BI to analyze financial transactions, customer behavior, transaction performance, fees, taxes, and regional trends.

## Dashboard Preview

### Overview Analysis

<img width="1476" height="757" alt="overview-dashboard" src="https://github.com/user-attachments/assets/197ad4fa-91ca-4f64-b6a7-11dde33755a7" />

### Transactions

<img width="1372" height="710" alt="transactions-dashboard" src="https://github.com/user-attachments/assets/34a5c6b9-225f-453b-8979-2f7bb2eff55a" />

---

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

---

## Business Requirements

The dashboard was developed to address the following analytical requirements:

- Monitor financial transaction performance
- Analyze monthly transaction trends
- Understand transaction success and failure
- Analyze customer segment contribution
- Compare state-wise performance
- Analyze transaction types
- Monitor fees and taxes
- Analyze transaction performance by gender
- Perform year-over-year analysis
- Provide detailed transaction-level information

The complete business requirements document is available here:

[View Business Requirements](https://github.com/Raoprajwal/finance-analytics-powerbi-dashboard/blob/main/Business%20Requirements.docx)

---

## Dashboard Pages

### 1. Overview Analysis

The Overview Analysis page provides a high-level view of financial performance using KPIs, charts, and interactive filters.

### 2. Transactions

The Transactions page provides detailed transaction-level records for deeper analysis.

---

## Key KPIs

The dashboard includes the following key performance indicators:

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax
- Year-over-Year (YoY) comparison

---

## Interactive Filters

Users can interact with the dashboard using:

- Year
- Dynamic Metrics
- Occupation
- Merchant Category

---

## Dashboard Visualizations

### Financial Performance

- Total Amount by Month
- Total Amount by Transaction Status
- Total Amount by Customer Segment
- Total Amount by State
- Total Amount by Gender

### Transaction Analysis

The Transaction Type Analysis provides:

- Transaction Amount
- Transaction Fees
- Transaction Tax
- Transaction Count

### Detailed Transactions

The Transactions page provides detailed records including:

- Transaction ID
- Transaction Date
- Customer Name
- Transaction Type
- Transaction Status
- Gender
- Customer Segment
- State
- Total Amount
- Total Fees
- Total Tax

---

## Data Preparation

Power Query was used to prepare the data before dashboard development.

The data preparation process included:

- Data type validation
- Text cleaning
- Handling missing values
- Column preparation
- Combining customer and transaction information
- Preparing fields required for analysis

---

## DAX & Time Intelligence

DAX measures were created for the main financial metrics and time-based analysis.

The project includes calculations for:

- Total Amount
- Total Fees
- Total Tax
- Total Transactions
- Average Transaction Value
- Previous Year Amount
- Year-over-Year analysis

A calendar table was used to support time-intelligence calculations.

---

## Dynamic Metrics

A Power BI Field Parameter was used to allow users to dynamically switch between selected financial measures within the dashboard.

This allows the same visual to display different metrics based on the user's selection.

---

## Data Model

The project uses two primary datasets:

### Customer Dataset

Contains customer information such as:

- Customer ID
- First Name
- Second Name
- Gender
- Date of Birth
- City
- State
- Occupation
- Customer Segment
- Annual Income
- Join Date

### Financial Transactions Dataset

Contains transaction information such as:

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

The datasets are connected using `customer_id`.

---

## Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- GitHub

---

## Repository Structure

```text
finance-analytics-powerbi-dashboard/
│
├── Data/
│   ├── customers.csv
│   └── finance_transactions.csv
│
├── Documentation/
│   └── data-dictionary.md
│
├── Power BI/
│   └── Financial_dashboard.pbix
│
├── Screenshots/
│   ├── overview-dashboard.png
│   └── transactions-dashboard.png
│
├── Business Requirements.docx
└── README.md
```

---

## Project Files

- [Download Power BI Dashboard](https://github.com/Raoprajwal/finance-analytics-powerbi-dashboard/blob/main/Power%20BI/Financial_dashboard.pbix)
- [View Customer Dataset](https://github.com/Raoprajwal/finance-analytics-powerbi-dashboard/blob/main/Data/customers.csv)
- [View Transaction Dataset](https://github.com/Raoprajwal/finance-analytics-powerbi-dashboard/blob/main/Data/finance_transactions.csv)
- [View Business Requirements](https://github.com/Raoprajwal/finance-analytics-powerbi-dashboard/blob/main/Business%20Requirements.docx)
- [View Data Dictionary](https://github.com/Raoprajwal/finance-analytics-powerbi-dashboard/blob/main/Documentation/data-dictionary.md)

---

## Disclaimer

This is a learning and portfolio project using sample data.

The datasets do not represent real customer information or confidential data from any financial institution.
