# Data Dictionary

This document describes the main fields used in the customer and financial transaction datasets for the Finance Analytics Dashboard.

## 1. Customer Dataset

| Column | Description |
|---|---|
| `customer_id` | Unique identifier assigned to each customer |
| `first_name` | Customer's first name |
| `second_name` | Customer's second name |
| `gender` | Customer gender |
| `date_of_birth` | Customer date of birth |
| `city` | Customer city |
| `state` | Customer state |
| `occupation` | Customer occupation |
| `customer_segment` | Customer business segment |
| `annual_income` | Customer annual income |
| `join_date` | Date on which the customer joined |

## 2. Financial Transactions Dataset

| Column | Description |
|---|---|
| `transaction_id` | Unique identifier for each transaction |
| `transaction_date` | Date on which the transaction occurred |
| `account_id` | Identifier of the account associated with the transaction |
| `customer_id` | Identifier linking the transaction to a customer |
| `transaction_type` | Type of financial transaction |
| `channel` | Channel through which the transaction was performed |
| `merchant_category` | Category associated with the merchant or transaction |
| `amount` | Transaction amount |
| `fee_amount` | Fee associated with the transaction |
| `tax_amount` | Tax associated with the transaction |
| `currency` | Currency used for the transaction |
| `transaction_status` | Status of the transaction |
| `is_fraud` | Indicator identifying whether the transaction is marked as fraudulent |
| `risk_score` | Risk score associated with the transaction |
| `reference_no` | Reference number associated with the transaction |

## 3. Relationship

The datasets can be connected using:

`customer_id`

The `customer_id` field identifies customers in the customer dataset and associates financial transactions with the corresponding customer.

## 4. Dashboard Usage

The datasets support analysis of:

- Transaction amounts
- Transaction volume
- Fees and taxes
- Transaction status
- Customer segments
- Geographic performance
- Transaction types
- Gender-wise transaction amounts
- Customer and transaction-level details
