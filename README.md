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



### 📊 Interactive Dashboard

You can view the live interactive Tableau dashboard here:

👉 [View Live Dashboard on Tableau Public[(<div class='tableauPlaceholder' id='viz1770744384842' style='position: relative'><noscript><a href='#'><img alt='Retail Revenue Cashflow Performance Analysis ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RetailRevenueandCashflowPerformance&#47;RetailRevenueCashflowPerformanceAnalysis&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RetailRevenueandCashflowPerformance&#47;RetailRevenueCashflowPerformanceAnalysis' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RetailRevenueandCashflowPerformance&#47;RetailRevenueCashflowPerformanceAnalysis&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1770744384842');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1500px';vizElement.style.height='877px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1500px';vizElement.style.height='877px';} else { vizElement.style.width='100%';vizElement.style.height='1627px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>)]


  




