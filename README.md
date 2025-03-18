# Suicide Rates Analysis (1990-2022)

## Project Overview
This project analyzes global suicide rates from 1990 to 2022 using various demographic, economic, and geographical factors. The dataset has been cleaned and processed to facilitate exploratory data analysis (EDA) and statistical insights.

## Dataset Information
### Raw Data (`age_std_suicide_rates_1990-2022.csv`)
- **Records:** 5,928
- **Columns:** 17
- **Key Features:**
  - **Geographic Information:** `RegionCode`, `RegionName`, `CountryCode`, `CountryName`
  - **Temporal Information:** `Year`
  - **Demographic Data:** `Sex`
  - **Suicide Data:** `SuicideCount`, `CauseSpecificDeathPercentage`, `StdDeathRate`, `DeathRatePer100K`
  - **Economic Indicators:** `GDP`, `GDPPerCapita`, `GNI`, `GNIPerCapita`, `InflationRate`, `EmploymentPopulationRatio`
- **Issues:** Missing values in economic indicators

### Cleaned Data (`cleaned_data.csv`)
- **Records:** 118,560
- **Columns:** 17 (including additional features)
- **Additional Features:**
  - `AgeGroup`
  - `Generation`
- **Data Cleaning:** Missing values handled, and additional attributes introduced for better insights.

## Project Files
### Jupyter Notebooks
1. [`cleaning.ipynb`](cleaning.ipynb) - Data preprocessing and cleaning
2. [`analysis.ipynb`](analysis.ipynb) - Exploratory Data Analysis (EDA), visualizations, and statistical insights

## Project Workflow
1. **Data Cleaning:**
   - Handled missing values
   - Standardized column names
   - Created new features (`AgeGroup`, `Generation`)
2. **Exploratory Data Analysis (EDA):**
   - Trends in suicide rates over time
   - Differences based on gender, age groups, and regions
   - Correlation with economic indicators
3. **Statistical Insights:**
   - Identifying high-risk demographics
   - Analyzing impact of GDP, employment, and inflation on suicide rates

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn, Plotly for analysis

## How to Run
1. Open [`cleaning.ipynb`](cleaning.ipynb) and run all cells to preprocess data.
2. Open [`analysis.ipynb`](analysis.ipynb) to explore insights and visualizations.

## Conclusion
This project provides a deep dive into global suicide trends, examining key economic and demographic influences. The findings can help policymakers and researchers understand risk factors and take preventive measures.

