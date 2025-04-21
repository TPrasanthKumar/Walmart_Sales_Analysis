Walmart Sales Analysis

Overview :
This project performs data cleaning and preprocessing on the Walmart sales dataset to prepare it for further analysis. The dataset includes weekly sales data across multiple stores, along with economic and environmental factors such as holiday flags, temperature, fuel prices, CPI, and unemployment rates.

Features:
Data Loading: Imports the Walmart sales dataset using pandas.
Data Cleaning:
Checks for and removes duplicate rows.
Handles missing values (none found in this dataset).
Converts column names to lowercase with underscores for consistency.
Converts the date column to datetime format.
Converts store and holiday_flag columns to categorical data types.
Exploratory Data Analysis:
Provides summary statistics for numerical columns.
Identifies unique values for categorical columns.
Data Export: Saves the cleaned dataset as Walmart_Sales_Cleaned.csv.Dataset

The dataset (Walmart_Sales.csv) contains the following columns:
store: Store ID (categorical)
date: Date of the sales record (datetime)
weekly_sales: Weekly sales amount (float)
holiday_flag: Indicator for holiday weeks (0 or 1, categorical)
temperature: Average temperature in the region (float)
fuel_price: Fuel price in the region (float)
cpi: Consumer Price Index (float)
unemployment: Unemployment rate (float)

Requirements
To run the analysis, ensure you have the following installed:
Python 3.8+
Libraries:
pandas
numpy (optional, for numerical operations)
