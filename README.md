# Data Cleaning & Preparation — Data Analytics Project 1

## Project Objective
Clean and prepare a raw e-commerce order dataset by identifying missing values, removing duplicates, correcting data types/formats, and validating the final dataset.

## Dataset
The raw Excel dataset contains 1,200 order records and 14 columns.

## Main Cleaning Tasks
1. Inspect the dataset and data types.
2. Identify missing values.
3. Treat missing `CouponCode` values as `No Coupon`.
4. Check and remove duplicate records.
5. Validate unique `OrderID` values.
6. Convert `Date` to datetime.
7. Convert quantity/cart fields to numeric integer types.
8. Convert price fields to numeric values and round to two decimal places.
9. Strip unnecessary whitespace from text fields.
10. Validate `TotalPrice = Quantity × UnitPrice`.
11. Export the cleaned CSV and Excel datasets.

## Files
- `Data_Cleaning_Preparation_Project.ipynb` — complete Python/Jupyter project
- `cleaned_dataset.csv` — cleaned dataset
- `cleaned_dataset.xlsx` — cleaned Excel dataset
- `data_quality_report.csv` — cleaning/validation summary

## Tools
- Python
- Pandas
- NumPy
- Jupyter Notebook
- Excel

## Result
The cleaned dataset contains 1,200 records after validation, with no missing values, no duplicate rows, no duplicate OrderIDs, valid dates, and no TotalPrice calculation mismatches.
