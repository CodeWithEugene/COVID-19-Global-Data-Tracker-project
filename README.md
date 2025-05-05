# Python Final Project: COVID-19 Data Analysis

## Overview
This project involves analyzing COVID-19 data to uncover insights about the pandemic's impact, vaccination progress, and trends across different countries. The analysis focuses on Kenya, the United States, and India, using data from the `owid-covid-data.csv` dataset.

## Key Steps

### 1. Data Loading
- The dataset is loaded using `pandas` and initial exploration is performed to understand its structure and identify missing values.

### 2. Data Exploration
- Key columns and their unique values are examined.
- Descriptive statistics for numerical columns such as `total_cases`, `total_deaths`, and `new_cases` are calculated.
- Visualizations, including histograms and a correlation heatmap, are created to understand data distributions and relationships.

### 3. Data Cleaning
- Data is filtered for the countries of interest: Kenya, the United States, and India.
- Missing values in critical columns are handled through interpolation and filling.
- The `date` column is converted to a datetime format for time-series analysis.

### 4. Data Preparation
- A `death_rate` column is calculated as `total_deaths / total_cases`.
- A separate vaccination DataFrame is created to analyze vaccination progress.
- Numeric columns are ensured to have consistent data types.

### 5. Data Analysis
- Descriptive statistics are grouped by country to compare metrics like mean, median, and maximum values for cases and deaths.
- Trends in total cases, deaths, and vaccinations over time are analyzed.
- Daily new cases and vaccination progress are compared across the three countries.

### 6. Data Visualization
- Line plots are created to visualize:
    - Total cases and deaths over time.
    - Daily new cases trends.
    - Vaccination progress over time.

## Insights
1. **Disparities in COVID-19 Impact**: The United States experienced the highest total cases and deaths, followed by India and Kenya.
2. **Vaccination Progress**: The United States led in vaccination rates, highlighting disparities in vaccine distribution.
3. **Daily New Cases**: The United States and India saw significant peaks in daily new cases, while Kenya's numbers remained relatively lower.
4. **Death Rate**: Variations in death rates reflect differences in healthcare systems and demographics.
5. **Correlation**: A strong positive correlation exists between total cases and deaths, emphasizing the importance of controlling the virus's spread.

## Next Steps
- Further explore anomalies, such as India's similar death rate to the United States despite fewer cases.
- Investigate factors influencing Kenya's slower vaccination rollout.
- Extend the analysis to include additional countries or time periods.

## Tools Used
- **Python Libraries**: `pandas`, `matplotlib`, `seaborn`
- **Dataset**: `owid-covid-data.csv`

This project provides a comprehensive analysis of COVID-19 data, offering valuable insights into the pandemic's trends and impact across different regions.  
