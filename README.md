# E-commerce Sales Analysis

## Overview

This portfolio project analyzes e-commerce sales data using SQL, Python, and Tableau.

An analytical dataset is extracted from Google BigQuery and then explored in Python to identify sales patterns across regions, product categories, devices, traffic channels, and customer groups, including statistical testing of differences between selected groups.

## Analysis

The project covers:

* Building an analytical dataset with SQL in Google BigQuery
* Dataset overview: column types, missing values, unique sessions, and date range
* Sales analysis by continent, country, and product category
* Sales analysis by device type, device model, and traffic source/channel
* Email verification and newsletter unsubscribe rates
* Sales dynamics over time, by day of the week, continent, traffic channel, and device
* Pivot tables combining sales by category, country, device, and continent
* Correlation analysis between sessions, sales, continents, traffic channels, categories, and device types
* Statistical testing of differences between groups using Mann-Whitney U, Friedman, two-proportion z-test, paired t-test, and Chi-square tests
* Interactive Tableau dashboard with key findings

## Technologies

* SQL
* Google BigQuery
* Python
* pandas
* Matplotlib
* SciPy
* statsmodels
* Tableau

## Result

The notebook `E_commerce_Sales_Analysis.ipynb` contains the complete analysis with visualizations, statistical tests, and business conclusions for each section.

The project also includes an interactive Tableau dashboard presenting the key findings.

## Content

### Exploratory_Data_Analysis_of_Global_Sales.ipynb

Jupyter Notebook containing the exploratory analysis of global sales data.

### E_commerce_Sales_Analysis.ipynb

Jupyter Notebook containing the e-commerce sales analysis, statistical testing, and visualizations.
