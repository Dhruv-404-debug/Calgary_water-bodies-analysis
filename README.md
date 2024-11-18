# Calgary Water Quality Analysis: pH Patterns and Temperature Correlation

## Overview
This project focuses on analyzing pH levels and their relationship with water temperature in Calgary’s water bodies, such as rivers, lakes, and streams. The study evaluates the health and stability of these water bodies, which are critical for both human use and aquatic ecosystems.

## This project aims to:

Estimate the current pH pattern in Calgary’s water bodies (January 1 to June 30, 2024).
Investigate the relationship between pH levels and water temperature.
Key Parameters:
Average pH: Calculate the average pH of Calgary's water bodies and estimate the range of the true mean pH level using confidence interval estimation.
pH-Temperature Relationship: Analyze how water temperature affects pH levels using simple linear regression.
Data Collection
The dataset comes from The City of Calgary’s in situ water quality monitoring program, accessed via the Open Calgary Data site. Key details include:

Collection Method: Multi-parameter sondes deployed in surface waters, recording measurements every 15 minutes and supplemented by discrete sampling.
Scope: Filtered to include data from January 1 to June 30, 2024.
Cleaning Process:
Removed missing or invalid values.
Restructured data for exploratory data analysis (EDA) and statistical modeling.
We acknowledge the data source under the Open Government Licence – City of Calgary.

## Methods
The project used two main analytical approaches:

Confidence Interval Estimation:

Estimated the average pH of Calgary’s water bodies.
Used bootstrapping to construct the confidence interval.
Linear Regression Analysis:

Modeled the relationship between water temperature and pH levels.
Evaluated statistical significance and predictive capability.
Results & Conclusions
Healthy pH Range:

Calgary’s water bodies have a mean pH confidence interval between 8.2843 and 8.2871, within the recommended range of 7 to 10.5 for healthy water quality.
Temperature and pH Relationship:

The regression analysis found a statistically significant but weak correlation between water temperature and pH levels.
The low R-squared value suggests that temperature alone does not significantly influence pH variations.
Implications for Water Management:

Other factors beyond temperature likely contribute to pH variability.
Future research should explore additional variables impacting pH to enhance water quality monitoring and management.

Acknowledgments
This project complies with the Open Government Licence – City of Calgary. We express gratitude to the City of Calgary for providing valuable water quality data for this analysis.

Dataset: https://data.calgary.ca/Environment/Water-Quality-Monitoring-Sonde-Data/kc8x-fu3f/about_data

