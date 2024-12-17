# Entry_ML_Phase1_AirQuality

This analysis focuses on the Air Quality Dataset, where the target variable is pollution levels in the environment. The goal is to predict the levels of pollutants such as CO, NO2, C6H6, and others based on meteorological and temporal attributes.

Dataset Overview:

Target Variable: Pollution levels (e.g., CO, NO2, C6H6).

Data Size: 9,471 rows and 17 columns.

Missing Values: Missing values are represented by ?. These were replaced with NaN, and imputation techniques like median or mean imputation were applied to handle missing values.

Duplicate Records: Identified and removed irrelevant or duplicate rows to ensure data integrity.
Outlier Detection and Handling: Outliers were detected using the Interquartile Range (IQR) method. Outliers in numerical features (e.g., pollutant concentrations, temperature, humidity) were capped or removed based on the lower and upper bounds of the IQR to prevent skewed model results.

Exploratory Data Analysis (EDA):
Visualizations were created to analyze the distribution of pollutants and their relationships with meteorological features such as temperature and humidity.

Correlation Analysis: Heatmaps were generated to assess correlations between pollutant levels and various environmental factors.
