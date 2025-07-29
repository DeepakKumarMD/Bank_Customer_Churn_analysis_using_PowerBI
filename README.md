# Bank_Customer_Churn_analysis_using_PowerBI

# Power BI Bank Customer Churn Analysis

## Project Overview

This project involves a comprehensive analysis of bank customer churn using Power BI. The primary objective is to identify the key factors that lead to customer churn, which is when customers stop using the bank's services. By understanding these factors, the bank can develop targeted strategies to improve customer retention and loyalty.

The project leverages a dataset containing various customer attributes, such as credit score, geography, age, and account balance. Through interactive dashboards and visualizations in Power BI, this project aims to provide actionable insights to business stakeholders. These insights will help in developing loyalty programs and retention campaigns to minimize customer churn.

## Business Problem

Customer churn is a significant challenge for banks. Acquiring new customers is often more expensive than retaining existing ones. Therefore, it is crucial for banks to understand the reasons why customers decide to leave. This project addresses the following business problems:

* **Identifying Key Drivers of Churn**: Determine the primary factors and customer segments that are most associated with churn.
* **Proactive Customer Retention**: Enable the bank to proactively identify at-risk customers and implement retention strategies.
* **Informing Business Strategy**: Provide data-driven insights to help the bank develop effective loyalty programs and improve overall customer satisfaction.

## Getting Started

### Prerequisites

* [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)

### Installation

1.  Clone the repository to your local machine:
    ```
    git clone [https://github.com/your-username/powerbi-bank-churn-analysis.git]
    ```
2.  Open the `customer_bank_churn_ongoing.pbix` file in Power BI Desktop.

## Data Dictionary

The dataset includes the following fields:

| Field             | Description                               | Data Type | Notes                               |
| ----------------- | ----------------------------------------- | --------- | ----------------------------------- |
| **RowNumber** | Record number                             | Integer   | No impact on the output             |
| **CustomerId** | Unique identifier for each customer       | Integer   | No impact on the output             |
| **Surname** | Customer's last name                      | Text      | No impact on the output             |
| **CreditScore** | Customer's credit score                   | Integer   | Higher score, less likely to churn  |
| **Geography** | Customer's location                       | Text      | Can affect the decision to leave    |
| **Gender** | Customer's gender                         | Text      | To be explored for its role in churn |
| **Age** | Customer's age                            | Integer   | Older customers are less likely to churn |
| **Tenure** | Number of years as a bank client          | Integer   | Older clients are more loyal        |
| **Balance** | Customer's account balance                | Decimal   | Higher balance, less likely to churn |
| **NumOfProducts** | Number of products purchased              | Integer   |                                     |
| **HasCrCard** | Whether the customer has a credit card    | Boolean   | 1 for yes, 0 for no                 |
| **IsActiveMember**| Whether the customer is an active member    | Boolean   | 1 for yes, 0 for no                 |
| **EstimatedSalary**| Customer's estimated salary               | Decimal   | Lower salary, more likely to churn   |
| **Exited** | Whether the customer left the bank        | Boolean   | 1 for churn, 0 for retained         |
| **BankDOJ** | Date the customer joined the bank         | Date      |                                     |

## Data Modeling

The data model for this project is designed to support a comprehensive churn analysis. The following data assets are used to create the model:

* `ActiveCustomer`
* `Bank_Churn`
* `CreditCard`
* `CustomerInfo`
* `ExitCustomer`
* `Gender`
* `Geography`

These tables are interconnected to create a relational model that allows for in-depth analysis of customer data and churn-related metrics.

## Power BI Dashboard

The Power BI dashboard provides an interactive and user-friendly interface to explore the churn data. The dashboard includes a variety of visualizations, such as:

* **Key Performance Indicators (KPIs)**: High-level metrics like churn rate, total customers, and average tenure.
* **Bar Charts**: Comparing churn rates across different geographies, genders, and age groups.
* **Donut Charts**: Showing the distribution of customers by credit score, number of products, and active member status.
* **Scatter Plots**: Analyzing the relationship between balance, estimated salary, and churn.
* **Slicers and Filters**: Allowing users to drill down into specific customer segments for a more granular analysis.

## Project Insights

The analysis of the customer churn data has revealed several key insights:

* **Credit Score is a Major Factor**: Customers with higher credit scores are significantly less likely to churn.
* **Geography Matters**: Churn rates vary by customer location, indicating that regional factors may play a role.
* **Age and Tenure are Key**: Older customers and those with a longer tenure at the bank are more loyal.
* **Account Balance is a Strong Indicator**: Customers with higher account balances are less likely to leave the bank.

These insights can be used to develop targeted retention strategies, such as offering personalized financial advice to customers with lower balances or providing loyalty rewards to long-term customers.
