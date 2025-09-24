# Dirty Cafe Sales: Data Cleaning and Analysis
This project focuses on cleaning a messy dataset of cafe sales transactions and then performing exploratory data analysis (EDA) to uncover insights and patterns.

# 1. Data Cleaning
The initial dataset contained several inconsistencies, including missing values and incorrect data types. The following steps were taken to clean the data:

Handled Missing Values:

Rows with missing Quantity values were removed to ensure the integrity of transaction records.

Corrected Data Types:

The Transaction Date column was converted from an object to a proper datetime format.

The Quantity, Price Per Unit, and Total Spent columns were converted to numeric types (int or float) to allow for calculations.

Cleaned Categorical Data:

Missing values in the Payment Method and Location columns, which were initially marked as "UNKNOWN", were filled in using the mode (the most frequently occurring value) for each respective column.

The cleaned data was then saved to a new file, ready for analysis.

# 2. Exploratory Data Analysis (EDA)
After cleaning the data, an exploratory analysis was conducted to understand the dataset better.

Statistical Summary:

Generated descriptive statistics for the numerical columns (Quantity, Price Per Unit, Total Spent) to get an overview of their distribution, central tendency, and spread.

Data Visualization:

Created various graphs to visualize relationships and distributions within the data:

Histograms to show the distribution of numerical data.

Bar Plots to compare sales across different categories like payment methods and locations.

A Heatmap to visualize the correlation between numerical variables.

These visualizations help in identifying key trends and patterns in the cafe's sales data.
