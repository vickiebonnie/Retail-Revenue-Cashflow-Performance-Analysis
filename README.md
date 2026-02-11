# Retail-Revenue-Cashflow-Performance-Analysis

![mini shop sales](https://github.com/user-attachments/assets/ebc42bd2-5e3c-4d56-8c7a-7f57df9bff40)


## Project Overview
A friend of mine owns a small neighborhood mini shop and was finding it increasingly difficult to track business performance as daily transactions increased. While sales were recorded regularly, it was not clear which products generated the most revenue, which customers purchased most frequently or how unpaid transactions were affecting cash flow.

As a result, restocking and business decisions were often based on assumptions rather than clear data insights. This project was developed to demonstrate how simple sales data can be structured and visualized to provide clarity on revenue performance, product demand and payment behavior.

The goal of the analysis is to show how data analytics can help small businesses move from intuition-based decisions to insight-driven operations.


## Business Objectives

The primary objective of this analysis is to use sales data to understand business performance and support data-driven decision-making for a small retail shop.

Specifically, the analysis aims to:

- Analyze total revenue performance and identify sales trends over time

- Identify the products contributing most to overall revenue

- Understand customer purchasing activity and transaction patterns

- Evaluate payment collection performance by comparing paid and unpaid sales

- Identify customers contributing most to outstanding balances to highlight potential cashflow risks

The objective is to demonstrate how structured data analysis and visualization can help small businesses monitor performance, improve inventory decisions and manage revenue collection more effectively



## Dataset & Tools


### Dataset
The dataset contains daily retail sales transactions recorded between November 2025 and January 2026 for a small mini shop selling fast-moving consumer goods. Each row represents a single product purchased within a transaction.

The dataset includes:

- Date — transaction date

- Items — product purchased

- Customer_ID — anonymized identifier used to protect customer identity

- Amount — value of each transaction

- Payment_Status — indicates whether the transaction was paid or remains unpaid

Customer names were replaced with unique IDs to ensure privacy while allowing customer-level analysis.


### Tools Used
Microsoft Excel

Excel was used for data preparation and structuring before analysis. This included:

- Standardizing inconsistent date formats

- Removing summary rows and non-transaction entries

- Structuring the dataset so that each row represented one product purchase

- Creating a clean tabular format suitable for visualization and aggregation

- Ensuring consistent product naming and payment status categories


Tableau

Tableau was used to transform the prepared dataset into an interactive analytical dashboard. Specifically:

- Creation of business KPIs (Total Revenue, Transactions, Customers, Unpaid Revenue, % Unpaid Revenue)

- Time-series visualization to analyze daily revenue trends

- Product-level revenue analysis to identify top-performing items

- Payment status analysis to evaluate revenue collection performance

- Identification of customers contributing most to outstanding balances



## Methodology

The analysis followed a structured data analysis workflow consisting of data preparation, transformation and visualization stages.

### Data Preparation

- Consolidated sales records into a single structured dataset

- Standardized date formats to enable accurate time-based analysis

- Removed non-transaction entries and ensured each row represented a single product purchase

- Anonymized customer information by replacing names with unique Customer IDs

- Standardized product names and payment status categories for consistency

### Data Analysis

- Aggregated transaction values to measure total revenue and daily sales performance

- Analyzed product-level revenue to identify top-performing items

- Compared paid and unpaid transactions to evaluate revenue collection performance

- Calculated key performance indicators including total revenue, transaction volume and  customer count.

## Key Insights


<img width="1499" height="849" alt="Retail Revenue Cashflow Performance Analysis" src="https://github.com/user-attachments/assets/3c446c25-38bb-4941-9e8d-ab1091529cb8" />


-  Revenue remained stable from November 2025 to January 2026, with a short decline in late December followed by recovery in January, indicating consistent demand.
  
- Sales performance is highly driven by a few key products — Kalypo, Simply Good Biscuit, and Cowbell Coffee contribute the largest share of revenue.
  
- 91% of revenue has been collected, while 9% remains outstanding, indicating moderate cashflow risk concentrated among a small group of customers.
  
-  Outstanding balances are driven mainly by a few customers, highlighting an opportunity to strengthen payment follow-ups and credit control.




### 📊 Interactive Dashboard

You can view the live interactive Tableau dashboard here:

👉 [View Live Dashboard on Tableau Public[(https://public.tableau.com/views/RetailRevenueandCashflowPerformance/RetailRevenueCashflowPerformanceAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]




  




