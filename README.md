## Dataset

Source: Unemployment in India (Kaggle)

## Key Columns:

Region – Indian state/region

Date – Date of data recording

Estimated Unemployment Rate (%) – Unemployment percentage

Estimated Employed – Number of employed individuals

Estimated Labour Participation Rate (%) – Participation rate of the labor force

##Project Workflow

##Import Libraries
Libraries used: pandas, numpy, matplotlib, seaborn.

##Data Loading
Loaded the dataset using pd.read_csv().

##Data Cleaning

##Removed duplicates and missing values.

##Standardized column names.

##Converted the Date column to datetime (dayfirst=True).

##Exploratory Data Analysis (EDA)

Summary statistics (.describe())

Value counts by region

Identification of time period and data coverage

Data Visualization

Bar plots: Unemployment rate by region

Line plot: Unemployment trend over time

Heatmap: Correlation between variables

COVID-19 Impact Analysis

Compared unemployment before and during the pandemic.

Added a new column Period (Before / During COVID).

Visualized differences with bar charts.

Regional Comparison

Analyzed unemployment by region during COVID-19 to identify most affected areas.
