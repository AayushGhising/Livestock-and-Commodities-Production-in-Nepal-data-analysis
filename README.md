# Livestock and Commodities Production in Nepal: Data Analysis

## Overview
This project analyzes livestock populations and agricultural commodity production across districts in Nepal. The analysis explores relationships between different livestock populations, milk production, meat production, and egg production to identify patterns and correlations that could inform agricultural policy and resource allocation.

## Dataset
The analysis uses multiple datasets related to livestock and agricultural production in Nepal:
- Horse/Asses population by district
- Milk animals (cows and buffaloes) and milk production by district
- Net meat production by district
- Cotton production by district
- Egg production by district
- Rabbit population by district
- Wool production by district
- Yak/Nak/Chauri population by district

## Methodology
1. **Data Preprocessing**:
   - Merged multiple datasets based on district names
   - Standardized district names and fixed inconsistencies
   - Handled missing values by filling with zeros
   - Converted appropriate columns to integer types
   - Filtered out non-district entries (totals, etc.)

2. **Exploratory Data Analysis**:
   - Statistical summaries of livestock populations and production figures
   - Examination of distribution of milk and egg production across districts
   - Correlation analysis between production outputs and animal populations

3. **Data Visualization**:
   - Scatter plots showing relationships between animal populations and production outputs
   - Box plots to visualize the distribution of milk production
   - Bar charts comparing production across districts
   - Pie charts showing the distribution of different types of milk
   - Correlation heatmaps for key production indicators

4. **Predictive Modeling**:
   - Linear regression models to predict milk production based on animal populations and meat production
   - Linear regression models to predict egg production based on laying hen and duck populations
   - Evaluation of model performance using MSE, MAE, and R² metrics

## Key Findings
- Strong correlations exist between milk-producing animal populations and total milk production
- Laying hen populations strongly predict egg production across districts
- Geographical variations in livestock populations and production figures highlight regional specialization

## Technologies Used
- Python for data manipulation and analysis
- Libraries:
  - Pandas for data manipulation
  - NumPy for numerical operations
  - Plotly Express for interactive visualizations
  - Scikit-learn for machine learning models and evaluation

## How to Run
1. Clone this repository
2. Install the required dependencies
3. Open the Jupyter notebook `Individual_Assignment_DAML.ipynb` to view the analysis
