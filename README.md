# Mean-Meadian-Mode-and-Percentile
**Overview**
This project involves data cleaning and analysis of two datasets: Income_Stats.xlsx and AB_NYC_2019.csv. The goal is to process these datasets by removing outliers, handling missing values, and preparing the data for further analysis.

**Datasets**
Income_Stats.xlsx: This dataset contains income statistics, and the analysis involves:

Displaying the first 20 rows and basic statistics.
Removing outliers by calculating the 99th percentile of the Income column.
Handling missing values by filling them with the mean and median of the Income column.
AB_NYC_2019.csv: This dataset contains Airbnb listings in New York City, and the analysis involves:

Describing the price column.
Removing outliers by calculating the 1st and 99.9th percentiles of the price column.
Filtering the dataset to include only listings within these thresholds.
Steps
Income_Stats.xlsx
Initial Analysis:

Display the first 20 rows.
Generate descriptive statistics.
Removing Outliers:

Calculate the 75th and 25th percentiles of the Income column.
Calculate the 99th percentile and filter out outliers above this threshold.
Create a new DataFrame without these outliers.
Handling Missing Values:

Introduce a missing value in the Income column.
Fill missing values with the mean and median of the Income column.
AB_NYC_2019.csv
Initial Analysis:

Display descriptive statistics for the price column.
Removing Outliers:

Calculate the 1st and 99.9th percentiles of the price column.
Filter the dataset to include only listings within these thresholds.
Display the shape of the filtered dataset and a sample of 5 rows.
Generate descriptive statistics for the price column in the filtered dataset.
Requirements
Python 3.x
pandas
numpy
Usage
Data Cleaning: The provided code snippets help in cleaning the datasets by removing outliers and handling missing values.
Further Analysis: The cleaned datasets are ready for further analysis, such as statistical analysis, data visualization, or machine learning.
