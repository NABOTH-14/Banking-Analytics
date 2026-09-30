# Banking Analytics Project

## Overview

This is a self-directed **Banking Analytics** project developed to demonstrate a practical end-to-end data analytics workflow.

The project simulates a banking environment containing customers, accounts, transactions, loans and branches. I worked through the process of **synthetic data generation, data quality assessment, cleaning, validation, exploratory analysis, data modelling and interactive dashboard development**.

The project combines **Python, Microsoft Excel and Microsoft Power BI** to demonstrate both technical and business-oriented data analytics skills.

> **Dataset Notice:** This project uses a simulated banking dataset created for portfolio and analytical demonstration purposes. It does not contain real customer, employee or transaction data.

---

## Project Objective

The objective was to transform raw simulated banking data into reliable and interactive business information that could support analysis and decision-making.

The project focuses on three main areas:

**Customer Analysis**
Understanding customer characteristics, segments and geographic distribution.

**Transaction Analysis**
Understanding transaction values, transaction types, channels, branches and trends over time.

**Loan Portfolio Analysis**
Understanding loan values, loan types, statuses, interest rates and loan terms.

---

## Data Model

The project contains five core tables:

| Table        | Records | Purpose                                                  |
| ------------ | ------: | -------------------------------------------------------- |
| Customers    |   1,000 | Customer demographic, geographic and segment information |
| Accounts     |   1,000 | Customer account information                             |
| Transactions |   6,003 | Banking transaction records                              |
| Loans        |     450 | Loan portfolio information                               |
| Branches     |      10 | Branch, city and province information                    |

The tables were connected in Power BI to create a relational data model that supports cross-table analysis.

### Key dimensions included

**Customers**

* Customer ID
* Age
* Gender
* Province
* City
* Branch
* Customer Segment
* Join Date

**Accounts**

* Account Type
* Account Status
* Opening Balance
* Account Open Date

**Transactions**

* Transaction Date
* Transaction Type
* Channel
* Branch
* Amount
* Transaction Status

**Loans**

* Loan Type
* Loan Amount
* Loan Status
* Application Date
* Interest Rate
* Loan Term

**Branches**

* Branch Name
* Province
* City

---

## Technology Stack

### Python

Python was used to create the **simulated banking dataset** and generate the structured records used throughout the project.

This provided an opportunity to work with programmatically generated data rather than relying only on manually created spreadsheets.

### Microsoft Excel

Excel was used for:

* Data quality assessment
* Data cleaning
* Validation checks
* Exploratory analysis
* Documentation of identified issues and corrective actions

### Microsoft Power BI

Power BI was used for:

* Data modelling
* Relationship management
* KPI development
* Data visualisation
* Interactive dashboard development
* Business analysis

---

## Data Quality Assessment

An important part of the project was assessing the reliability of the raw data before building the dashboard.

The profiling process identified issues including:

* Missing customer gender values
* Inconsistent geographical naming
* Duplicate transaction records
* Missing transaction amounts
* Missing transaction identifiers
* Inconsistent transaction channel formatting
* Zero transaction amounts
* Negative transaction amounts
* Province and city inconsistencies

The issues were documented through a **data profile, data quality review, cleaning log and validation checks**.

### Examples

* **4 missing Gender values** were identified in the Customers table.
* **3 duplicate Transaction records** were identified.
* **4 missing transaction Amount values** were identified.
* A transaction with an **Amount of 0** was flagged.
* A transaction with an **Amount of -500** was flagged.
* Geographical inconsistencies involving province and city information were reviewed and corrected.
* Referential integrity between related tables was checked.

This process was used to distinguish genuine business information from potential data-quality problems.

---

## Key Dashboard KPIs

The Power BI dashboard currently reports:

### Total Transaction Value

**K7,996,510.84**

### Valid Transaction IDs

**6,000**

There are 6,003 transaction records in the dataset, but three Transaction IDs are missing. The dashboard therefore uses the count of non-blank Transaction IDs as a data-quality-aware KPI.

### Total Loan Value

**K10,018,521.75**

---

## Dashboard Analysis

The Power BI dashboard provides interactive analysis across several areas.

### Transaction Analysis

* Transaction Value by Branch
* Transaction Value by Transaction Type
* Transaction Value by Channel
* Monthly Transaction Value

Transaction types include:

* Deposits
* Payments
* Transfers
* Withdrawals
* Loan Repayment

Transaction channels include:

* Mobile Banking
* ATM
* Branch
* Internet Banking
* POS

### Loan Analysis

* Loan Value by Status
* Loan Value by Loan Type

Loan statuses include:

* Active
* Paid
* Rejected
* Defaulted

Loan types include:

* Personal
* SME
* Salary Advance
* Agricultural

### Customer Analysis

* Customers by Province
* Customer segmentation within the underlying dataset

The simulated customers span six provinces:

* Lusaka
* Copperbelt
* Western
* Eastern
* Central
* Southern

---

## Interactive Dashboard Features

The dashboard includes interactive slicers for:

* Branch
* Transaction Type
* Transaction Period

These allow users to filter the dashboard and investigate specific branches, transaction categories and time periods.

---

## Business Questions

The project was designed to answer practical banking questions such as:

* What is the total value of transactions?
* Which branches generate the highest transaction values?
* Which transaction types contribute most to transaction value?
* Which channels contribute most to transaction value?
* How does transaction value change over time?
* What is the total loan portfolio value?
* How is the loan portfolio distributed by status?
* Which loan types represent the largest part of the portfolio?
* How are customers distributed geographically?
* What data-quality issues could affect business reporting?

---

## Skills Demonstrated

This project demonstrates practical experience in:

* Python
* Synthetic data generation
* Data cleaning
* Data quality assessment
* Data profiling
* Data validation
* Exploratory data analysis
* Excel
* Relational data modelling
* Power BI
* KPI development
* Interactive dashboard design
* Business intelligence
* Data visualisation
* Business-focused data analysis
* Data storytelling

---

## Project Workflow

```text
Python
   ↓
Synthetic Banking Data Generation
   ↓
Excel
   ↓
Data Profiling → Data Quality Checks → Cleaning → Validation
   ↓
Power BI
   ↓
Data Modelling → Analysis → Visualisation → Interactive Dashboard
```

---

## Project Structure

```text
Banking-Analytics/
│
├── README.md
├── Banking_Analytics.pbix
├── Banking_Analytics_Dataset.xlsx
└── dashboard.png
```

---

## Purpose

The purpose of this project is to demonstrate how raw structured data can be transformed into reliable business information through a disciplined analytics workflow.

It reflects my ongoing development in **Data Analytics, Business Intelligence, Python and AI**, with a particular interest in applying quantitative and analytical thinking to real-world business problems.

---

## Author

**Naboth Alinaswe Mulenga**

**BSc Pure Mathematics and Applied Statistics**

Focus: **Data Analytics | Business Intelligence | Python | AI**


