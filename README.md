# Airbnb-Pricing-ML-Pipeline
A Machine Learning pipeline in R predicting short-term rental prices and identifying key market drivers in the Minneapolis-Saint Paul market.

# Airbnb Short-Term Rental Price Prediction: Minneapolis-Saint Paul

## Overview
A comprehensive Machine Learning pipeline built to predict short-term rental prices and identify key market drivers across the Minneapolis-Saint Paul market. 

## Tech Stack
* **Language:** R
* **Techniques:** Exploratory Data Analysis (EDA), Outlier Remediation, Ensemble Learning
* **Models:** Random Forest, Bagging

## Methodology & Results
* Processed and cleaned a dataset of 3,700+ Airbnb listings, specifically handling outlier remediation on a heavily right-skewed target variable (max: $5,556/night).
* Engineered train/test splits and ensured categorical feature alignment across the data.
* Trained and compared Bagging versus Random Forest ensemble models utilizing 500 trees each.
* **Outcome:** The Random Forest model outperformed Bagging, achieving a lower Out-of-Bag (OOB) Mean Squared Error (7,818 vs. 8,176) through effective tree decorrelation.
* **Business Insights:** Utilized permutation importance (%IncMSE) to identify `bathrooms`, `accommodates`, and `dist_to_downtown` as the primary pricing drivers, while proving host review scores were statistically insignificant.

*(Note: See the included Technical and Final PDF reports for full methodology, visualizations, and business intelligence breakdowns.)*
