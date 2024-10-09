COVID-19 Data Analysis - EDA (Exploratory Data Analysis)

Overview

This project involves an Exploratory Data Analysis (EDA) on a dataset containing global COVID-19 data. The goal of the analysis is to understand the distribution of confirmed cases, deaths, recoveries, and other related metrics across different countries. The dataset was analyzed to derive key insights such as Case Fatality Rate (CFR), Recovery Rate, and to identify trends, outliers, and anomalies in the data.

Dataset Information

The dataset used in this project includes the following columns:

Country/Region: The country or region name.
Confirmed: The total number of confirmed COVID-19 cases.
Deaths: The total number of deaths from COVID-19.
Recovered: The total number of recovered cases.
Active: The number of active cases.
New cases: The number of new confirmed cases.
New deaths: The number of new deaths.
New recovered: The number of new recovered cases.
Deaths / 100 Cases: The percentage of deaths per 100 confirmed cases.
Recovered / 100 Cases: The percentage of recoveries per 100 confirmed cases.
Deaths / 100 Recovered: The percentage of deaths per 100 recovered cases.
Confirmed last week: The confirmed cases from the previous week.
1 week change: The change in confirmed cases over one week.
1 week % increase: The percentage increase in confirmed cases over one week.
WHO Region: The WHO region the country belongs to.
Analysis Steps

1. Data Cleaning and Preprocessing
Checking for Missing Values: We identified and handled any missing or null values in the dataset.
Data Types: We ensured that the data types of columns were appropriate (e.g., numerical columns for cases, deaths, etc.).
Date Conversion: If applicable, the 'Date' column was converted to a datetime type for proper time-based analysis.
2. Descriptive Statistics
Statistical Summaries: We calculated the mean, median, and standard deviation for the numerical columns to understand the data distribution.
Outliers and Extreme Values: We identified countries with exceptionally high or low values in metrics like confirmed cases and deaths.
3. Calculation of Key Metrics
Case Fatality Rate (CFR): CFR was calculated as (Deaths / Confirmed) * 100 for each country.
Recovery Rate: Recovery Rate was calculated as (Recovered / Confirmed) * 100 for each country.
4. Top 10 Countries by Key Metrics
Top 10 Countries by Confirmed Cases, Deaths, and Recoveries: We visualized the top 10 countries based on each metric.
Top 10 Countries by CFR and Recovery Rate: These metrics were analyzed to understand the relative impact of COVID-19 in different countries.
5. Visualization
Bar Charts: We used bar charts to visualize the top 10 countries for confirmed cases, deaths, recoveries, CFR, and recovery rates.
Comparison Plots: Comparison of different metrics across countries was visualized to identify trends, anomalies, and relationships.
Key Insights

Top Affected Countries: The United States, Brazil, and India have the highest number of confirmed cases.
CFR and Recovery Rate: The United Kingdom exhibited an unusually high Case Fatality Rate, suggesting possible reporting or management anomalies.
Recovery Rates: Countries like Brazil and Mexico showed significant recovery rates, indicating better management or reporting of recoveries.
Technologies and Libraries Used

Python: Main programming language used for analysis.
Pandas: For data manipulation and analysis.
Matplotlib: For data visualization (bar charts, comparisons).
NumPy: For numerical operations and calculations.
Jupyter Notebook: For running and documenting the analysis.
Requirements

To run the code, you can install the required libraries using the requirements.txt file. Here's the list of libraries used:
pandas
matplotlib
numpy
To install the dependencies, run:


pip install -r requirements.txt

How to Run the Code

Download the dataset from the provided source (e.g., covid_data.csv).
Clone or download this repository.
Run the eda.ipynb notebook in Jupyter Notebook or JupyterLab to execute the analysis.
