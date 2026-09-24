# Ecommerce_Sales_Dataset_Cleaning


#  E-Commerce Dataset Cleaning Project

##  Project Overview

This project focuses on cleaning and preprocessing an e-commerce dataset using **Python and Pandas**. The objective is to transform raw e-commerce data into clean, consistent, and analysis-ready datasets that can be used for **data analysis and Power BI dashboard development**.

The project covers customer, sales, order-item, and product information.

##  Objectives

* Clean and preprocess raw e-commerce datasets
* Identify and remove duplicate records
* Handle missing values appropriately
* Correct invalid and inconsistent data
* Standardize text and column names
* Convert columns into appropriate data types
* Validate numerical and categorical values
* Export clean datasets for further analysis

##  Datasets Used

The project contains four major datasets:

| Dataset                                       | Description                                             |
| --------------------------------------------- | ------------------------------------------------------- |
| `customer_master.csv`                         | Customer information and acquisition details            |
| `ecommerce_sales_customer_analytics_150k.csv` | Sales, customer, order, delivery and review information |
| `order_items.csv`                             | Order-level product and transaction details             |
| `product_catalog.csv`                         | Product, pricing, cost and rating information           |

##  Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**
* **VS Code**
* **Power BI**

##  Data Cleaning Process

### 1. Data Loading

Loaded multiple CSV files using Pandas.

### 2. Data Exploration

Examined:

* Dataset dimensions
* Column names
* Data types
* Missing values
* Duplicate records

### 3. Duplicate Removal

Identified and removed duplicate records to improve data consistency.

### 4. Column Standardization

Cleaned column names and removed unnecessary spaces from text values.

### 5. Missing Value Treatment

Handled missing values using appropriate methods such as:

* Median imputation for numerical fields
* Meaningful categories such as `No Review`, `No Coupon`, and `Not Returned`

### 6. Data Type Conversion

Converted numerical and date columns into appropriate data types for accurate analysis.

### 7. Invalid Value Handling

Identified and corrected invalid values such as:

* Invalid customer ages
* Negative prices
* Invalid quantities
* Invalid discount percentages
* Invalid customer ratings
* Negative delivery days

### 8. Data Validation

Performed final checks for:

* Remaining missing values
* Duplicate records
* Data consistency
* Dataset dimensions

### 9. Exporting Clean Data

Saved the cleaned datasets as CSV files for further analysis and visualization.

##  Key Cleaning Areas

The project specifically focuses on cleaning:

* Customer information
* Sales transactions
* Product information
* Order items
* Prices and costs
* Discounts
* Customer ratings
* Delivery information
* Returns
* Reviews
* Campaigns and coupons

##  Outcome

The raw datasets were transformed into **clean, structured, and analysis-ready datasets**. The cleaned data can be used to build Power BI dashboards and generate insights into:

* Sales performance
* Revenue and profit
* Customer behavior
* Product performance
* Orders and transactions
* Discounts
* Returns
* Customer ratings
* Delivery performance

##  Key Learning

This project helped strengthen practical skills in **data preprocessing, data quality validation, missing-value handling, duplicate detection, data type conversion, and preparing datasets for business intelligence and visualization**.

##  Future Scope

The cleaned datasets can be further used to develop an interactive **Power BI E-Commerce Analytics Dashboard** with KPIs, charts, filters, customer analysis, product performance, sales trends, and profitability insights.

##  Tools

```text
Python | Pandas | NumPy | Jupyter Notebook | VS Code | Power BI
```

