# COVID-19 Global Data Tracker Project

### COVID-19 Data Analysis: Africa Focus
## Overview
This project analyzes global COVID-19 data using Python and Jupyter Notebook. It focuses on data manipulation, visualization, and statistical analysis to understand the pandemic's trends, particularly in Africa.
- the url to the dataset website https://covid.ourworldindata.org/data/owid-covid-data.csv
## Features
1. **Data Loading**:
   - Reads the `owid-covid-data.csv` dataset using `pandas`.
   - Handles errors like missing files or unexpected issues.

2. **Data Inspection**:
   - Displays data types and counts missing values for each column.
   - Outputs the first few rows of the dataset for quick inspection.

3. **Filtering for Africa**:
   - Filters the dataset to include only rows where the `continent` column equals "Africa".
   - Further filters data for specific African countries using the `location` column.

4. **Data Cleaning**:
   - Identifies and drops columns with excessive missing values.
   - Handles missing data and duplicates in the filtered dataset.

5. **Visualization**:
   - Line plots for total cases and deaths over time in Africa.
   - Bar plots for positivity rates and total cases by country.
   - Scatter plots with regression lines to analyze the relationship between new tests and new cases.

6. **Statistical Analysis**:
   - Trains a linear regression model to predict new cases based on new tests.
   - Provides insights into testing and case trends.

## Requirements
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `numpy`, `scikit-learn`

## How to Run
1. Install required libraries:
