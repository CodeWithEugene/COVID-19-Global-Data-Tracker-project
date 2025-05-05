# Python Final Project: COVID-19 Data Analysis

## Overview
In this project, I analyzed COVID-19 data to uncover insights about the pandemic's impact, vaccination progress, and trends across three countries: Kenya, the United States, and India. I used the `owid-covid-data.csv` dataset as the primary data source for this analysis.

## Key Steps

### 1. Data Loading
I started by loading the dataset using `pandas`. Initial exploration helped me understand its structure, identify key columns, and locate any missing values.

### 2. Data Exploration
I examined the unique values in key columns and calculated descriptive statistics for numerical data, such as `total_cases`, `total_deaths`, and `new_cases`. To better understand the data, I created visualizations like histograms and a correlation heatmap.

### 3. Data Cleaning
I filtered the dataset to focus on Kenya, the United States, and India. Missing values in critical columns were addressed using interpolation and filling techniques. Additionally, I converted the `date` column to a datetime format to facilitate time-series analysis.

### 4. Data Preparation
To enhance the analysis, I calculated a new column, `death_rate`, as `total_deaths / total_cases`. I also created a separate DataFrame to specifically analyze vaccination progress. Numeric columns were standardized to ensure consistent data types.

### 5. Data Analysis
I grouped descriptive statistics by country to compare metrics like mean, median, and maximum values for cases and deaths. I analyzed trends in total cases, deaths, and vaccinations over time, and compared daily new cases and vaccination progress across the three countries.

### 6. Data Visualization
I used line plots to visualize:
- Total cases and deaths over time.
- Trends in daily new cases.
- Vaccination progress over time.

## Insights
1. **Disparities in COVID-19 Impact**: The United States recorded the highest total cases and deaths, followed by India and Kenya.
2. **Vaccination Progress**: The United States led in vaccination rates, highlighting disparities in vaccine distribution.
3. **Daily New Cases**: Significant peaks in daily new cases were observed in the United States and India, while Kenya's numbers remained relatively lower.
4. **Death Rate**: Variations in death rates reflected differences in healthcare systems and demographics.
5. **Correlation**: A strong positive correlation existed between total cases and deaths, emphasizing the importance of controlling the virus's spread.

## Next Steps
- Investigated anomalies, such as India's similar death rate to the United States despite fewer cases.
- Explored factors contributing to Kenya's slower vaccination rollout.
- Extended the analysis to include additional countries or longer time periods.

## Tools Used
- **Python Libraries**: `pandas`, `matplotlib`, `seaborn`
- **Dataset**: `owid-covid-data.csv`

This project provided a detailed analysis of COVID-19 data, offering valuable insights into the pandemic's trends and its impact across different regions.  
