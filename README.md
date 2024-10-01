# BookstoreSalesDataCleaning

## Project Overview

This project focuses on cleaning and analyzing bookstore sales data, comprising 2000 records of customer purchases. The dataset includes customer details such as names, email addresses, phone numbers, and purchase information. The goal of this project is to clean the raw data, handle missing or inconsistent values, and ensure the dataset is ready for further analysis.

## Key Objectives
- **Handle Missing Data**: Replace missing values in `Email`, `PhoneNumber`, and `Address` with default values ("Unknown" or "00000").
- **Standardize Data Formats**: Ensure consistent formatting for `PhoneNumber` by replacing `x` and `.` with `-`, and convert `PurchaseDate` to a datetime format.
- **Data Validation**: Filter out invalid purchase amounts and ensure all numerical values are properly formatted.
- **Data Integrity**: Remove duplicate entries based on `CustomerID` to maintain the uniqueness of each customer.

## Tools Used
- **Python**: For data cleaning and analysis.
- **Pandas**: To handle missing data, perform transformations, and ensure data consistency.
- **NumPy**: For efficient handling of numerical data.

## Files in the Repository
- **Initial_DataBookstoreSales.csv**: The original raw dataset.
- **Cleaned_DataBookstoreSales.csv**: The cleaned and processed dataset, ready for analysis.
- **data_cleaning_script.py**: Python script used to perform data cleaning operations.
  


