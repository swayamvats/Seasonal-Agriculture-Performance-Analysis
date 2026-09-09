# Seasonal Agriculture Performance Analysis

## About the Project

This project focuses on analyzing agricultural performance across different seasons.

The dataset contains information about crops, geographical areas, environmental conditions, farming practices, resource usage and economic performance.

The main purpose of this project is to understand how agricultural performance changes across seasons and identify useful patterns, trends and relationships in the data.

## Problem Statement

Agricultural performance can change from one season to another because of environmental conditions, farming practices, resource availability and market conditions.

In this project, I analyzed the given agricultural dataset to identify seasonal differences in agricultural performance and understand the patterns and variations present in the data.

## Objectives

- To understand the agricultural dataset
- To clean and prepare the data for analysis
- To compare agricultural performance across different seasons
- To identify seasonal patterns and trends
- To study environmental conditions and their relationship with agricultural outcomes
- To analyze resource usage across seasons
- To compare crop and state-wise performance
- To analyze economic performance such as cost, revenue and profit
- To identify unusual patterns and variations
- To use suitable statistical and visualization techniques
- To provide conclusions and recommendations based on the analysis

## Dataset

The dataset contains **4,000 rows and 28 columns**.

It includes information related to:

- Season
- Crop
- State
- District
- Farm Area
- Rainfall
- Average Temperature
- Humidity
- Sunlight Hours
- Soil pH
- Soil Moisture
- Nitrogen
- Phosphorus
- Potassium
- Fertilizer Usage
- Pesticide Usage
- Seed Quality
- Water Usage
- Water Efficiency
- Yield
- Production
- Market Price
- Total Cost
- Revenue
- Profit
- Disease/Pest Risk
- Irrigation Method

## Data Cleaning

The following data preparation steps were performed:

- Checked the number of rows and columns
- Checked data types and dataset information
- Checked missing values
- Checked duplicate records
- Handled missing values in rainfall and soil moisture using median values based on crop and season
- Yield missing values were kept as missing and excluded from yield-specific analysis
- Created a cleaned dataset for further analysis

## Analysis Performed

### 1. Seasonal Analysis

Agricultural performance was compared across:

- Kharif
- Rabi
- Zaid

Average yield and yield variations were analyzed for different seasons.

### 2. Environmental Analysis

Environmental conditions were compared across seasons, including:

- Rainfall
- Average Temperature
- Humidity
- Sunlight Hours
- Soil Moisture

### 3. Resource Usage Analysis

The project analyzed the usage of different agricultural resources such as:

- Water
- Fertilizer
- Pesticide
- Nitrogen
- Phosphorus
- Potassium

### 4. Irrigation Analysis

Different irrigation methods were compared using agricultural performance measures such as yield, water usage and profit.

### 5. Crop Analysis

Different crops were compared based on their average yield and other performance measures.

Crop performance across different seasons was also analyzed.

### 6. State-wise Analysis

Agricultural performance was compared across different states to identify regional variations.

### 7. Economic Analysis

Economic performance was analyzed using:

- Market Price
- Total Cost
- Revenue
- Profit

### 8. Correlation Analysis

Correlation analysis was performed to understand relationships between important agricultural variables and yield.

### 9. Disease and Pest Risk Analysis

Disease and pest risk was analyzed across different seasons to identify variations in agricultural risk.

### 10. Outlier Analysis

Outlier analysis was performed using visualizations to identify unusual observations in important numerical variables.

### 11. Statistical Analysis

The **Kruskal-Wallis test** was used to check whether there was a significant difference in yield across different seasons.

## Key Findings

- **Kharif** had the highest average yield of approximately **5.64 tonnes/ha**
- **Zaid** had the lowest average yield of approximately **4.67 tonnes/ha**
- **Kharif** had the highest average profit of approximately **₹178,914.65**
- **Sugarcane** had the highest average yield among the analyzed crops, approximately **46.94 tonnes/ha**
- **Punjab** had the highest average yield among the analyzed states, approximately **6.12 tonnes/ha**
- Agricultural performance varied across different seasons, crops and states
- Environmental conditions and resource usage also showed variations across seasons
- The Kruskal-Wallis test showed a statistically significant difference in yield across seasons

## Tools and Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Google Colab**
- **Jupyter Notebook**

## Project Workflow

**Dataset → Data Loading → Data Exploration → Data Cleaning → Seasonal Analysis → Environmental Analysis → Resource Usage → Irrigation Analysis → Crop Analysis → State Analysis → Economic Analysis → Correlation Analysis → Risk Analysis → Outlier Analysis → Statistical Testing → Findings → Recommendations → Conclusion**

## Recommendations

- Seasonal differences should be considered while planning agricultural activities
- Crop selection can be planned according to seasonal performance
- Water and other resources should be monitored according to seasonal requirements
- Environmental conditions such as rainfall and soil moisture should be considered during planning
- Irrigation methods can be compared based on water usage, yield and profit
- Economic factors such as cost, revenue and profit should be considered along with production
- Unusual observations and high-risk conditions can be investigated further

## Conclusion

This project helped in understanding how agricultural performance changes across different seasons.

The analysis covered data cleaning, seasonal yield comparison, environmental conditions, resource usage, irrigation methods, crop performance, state-wise comparison, economic performance, correlation analysis, disease and pest risk, outlier analysis and statistical testing.

The results provide useful insights into seasonal differences in agricultural performance and can support better seasonal agricultural planning.

## Future Scope

The project can be extended in the future by:

- Adding more years of agricultural data
- Including more weather and environmental information
- Applying machine learning models for crop yield prediction
- Performing more detailed regional analysis
- Creating an interactive dashboard
- Using larger datasets for better analysis and prediction

## Project Files

- `Seasonal_Agriculture_Performance_Analysis.ipynb` - Main analysis notebook
- `seasonal_agriculture_performance_dataset.csv` - Dataset
- `README.md` - Project documentation

## Author

**Swayam Jha**

BCA Student  
Data Analytics Project
