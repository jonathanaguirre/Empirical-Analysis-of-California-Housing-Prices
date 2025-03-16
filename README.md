# Empirical Analysis of California Housing Prices

## Introduction
Let's predict the cost of homes in parts of California using Python and the Scikit-learn library. From the housing.csv file, nine Feature variables and one target variable will be utlized. Linear Regresson, Random Forest Regressor, and XGBoost will be used in Model Training.

## What is the Target Variable?
medianHouseValue: Median house value for households within a block (measured in US Dollars).

## What Feature Variables are there?
| Feature              | Description                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------|
| longitude            | A measure of how far west a house is (a higher value is farther west).                        |
| latitude             | A measure of how far north a house is (a higher value is farther north).                      |
| housingMedianAge     | Median age of a house within a block (a lower number implies a newer building).                |
| totalRooms           | Total number of rooms within a block.                                                          |
| totalBedrooms        | Total number of bedrooms within a block.                                                       |
| population           | Total number of people residing within a block.                                               |
| households           | Total number of households, where a household unit is comprised of a group of people for some block. |
| medianIncome         | Median income for households within a block of houses (measured in tens of thousands of US Dollars). |
| oceanProximity       | Location of the house in proximity to the ocean.                                              |


## What dependencies are required?
| Package      | Description                                                                                   |
|--------------|-----------------------------------------------------------------------------------------------|
| math         | A standard library in Python for mathematical functions and constants.                        |
| pandas       | A library for data manipulation and analysis, providing data structures like DataFrames.      |
| matplotlib   | A plotting library for creating static, animated, and interactive visualizations in Python.  |
| seaborn      | A statistical data visualization library based on matplotlib, providing a high-level interface.|
| scikit-learn | A machine learning library for Python, offering simple and efficient tools for data mining and analysis. |
| numpy        | A library for numerical computations in Python, providing support for large, multi-dimensional arrays and matrices. |
| xgboost      | An optimized gradient boosting library designed to be highly efficient, flexible, and portable. |
