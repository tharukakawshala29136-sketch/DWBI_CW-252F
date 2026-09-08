# Day 04 – ETL Pipeline

## Overview

This project implements an ETL (Extract, Transform, Load) pipeline using the Supermarket Sales dataset.

The pipeline is developed using Python and Pandas in Google Colab. The main purpose is to extract raw supermarket sales data, clean and transform the data, perform data validation, and prepare the data for loading into a data warehouse structure.

## Dataset

The dataset used for this project is the Supermarket Sales dataset.

The dataset contains sales transactions with information about:

- Invoice ID
- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Tax
- Sales
- Date
- Time
- Payment Method
- COGS
- Gross Margin Percentage
- Gross Income
- Rating

## ETL Pipeline

The ETL pipeline consists of the following stages:

### 1. Extract

The raw Supermarket Sales CSV file is uploaded and loaded into a Pandas DataFrame using Python.

### 2. Data Profiling and Cleaning

The dataset is checked for:

- Missing values
- Duplicate records
- Data types
- Invalid values
- Unnecessary spaces in text fields

### 3. Transform

The data is transformed to make it suitable for analysis and data warehousing.

The transformations include:

- Converting Date into datetime format
- Converting Time into time format
- Extracting Year
- Extracting Month
- Extracting Day
- Extracting Quarter
- Extracting Day of Week
- Extracting Hour
- Creating Time Periods
- Creating calculated sales-related fields
- Standardizing categorical values
- Performing data validation

### 4. Data Warehouse Preparation

The transformed data is organized into dimension and fact tables.

The planned tables include:

- DimDate
- DimBranch
- DimProduct
- DimCustomer
- DimPayment
- FactSales

### 5. Load

The transformed dimension and fact tables are saved as CSV files for further use in the data warehouse and analytical processes.

## Tools and Technologies

- Python
- Pandas
- Google Colab
- Jupyter Notebook

## Project Structure

```text
04/
│
├── README.md
├── ETL_Day04.ipynb
├── SuperMarket Analysis.csv
└── Screenshot 2026-09-03 113951.png
