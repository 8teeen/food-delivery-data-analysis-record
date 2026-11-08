# Food Delivery Data Analysis

## Project Overview
This project focuses on understanding and cleaning a food delivery dataset using Python and Pandas.

The objective of Week 1 is to inspect the dataset, identify data quality issues, perform appropriate cleaning, and prepare the data for further analysis.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook
- Git and GitHub

## Dataset Information
- Total records: 45,584
- Total columns: 20
- Duplicate rows: 0
- Duplicate IDs: 0
- Missing values after cleaning: 9,184

Each row represents a food delivery record, based on the available dataset fields.

## Data Cleaning Performed
- Removed leading and trailing whitespace.
- Corrected the city spelling inconsistency.
- Converted Order_Date into datetime format.
- Standardized order and pickup time representations.
- Checked numeric values and rating ranges.
- Identified and retained missing values where no justified replacement was available.
- Checked duplicate rows and IDs.

## Project Structure
food-delivery-data-analysis/
- data/raw/
- data/processed/
- notebooks/
- docs/
- README.md
- requirements.txt

## Week 1 Outcome
The cleaned dataset was exported to:
data/processed/cleaned_food_delivery.csv

The original dataset was preserved separately.

## Author
Computer Engineering Student
