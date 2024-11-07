# Car Insurance Claim Prediction Project

This project analyzes factors affecting the likelihood of car insurance claims. Using **logistic regression models**, it identifies significant predictors to help insurers assess risk and improve decision-making.

## Project Overview

Insurance companies rely on data to assess the risk associated with different policyholders. This project uses a dataset of car insurance clients and explores various demographic, financial, and vehicle-related features to predict claim likelihood.

## Dataset

The dataset includes the following key columns:

- `age`: Age of the client
- `gender`: Gender of the client
- `driving_experience`: Years of driving experience categorized into ranges
- `education`: Education level of the client
- `income`: Income category
- `credit_score`: Numerical credit score of the client
- `vehicle_ownership`: Indicator of whether the client owns their vehicle
- `vehicle_year`: Year of the vehicle’s registration
- `married`: Marital status of the client
- `children`: Number of children
- `annual_mileage`: Annual mileage driven
- `vehicle_type`: Type of vehicle (e.g., sedan, sports car)
- `speeding_violations`: Number of speeding violations
- `duis`: Number of driving under the influence (DUI) incidents
- `past_accidents`: Number of past accidents
- `outcome`: Target variable indicating whether the client made an insurance claim

## Key Findings

The project identified **driving experience** as the most influential predictor, with an accuracy of **77.71%** in the model. This insight suggests that driving experience is a strong indicator of claim likelihood, potentially guiding insurance premium calculations and risk assessments.


## Future Work

Further exploration could include:

- Building a multi-feature logistic regression model to capture interaction effects between variables.
- Investigating the impact of other demographic factors on claim frequency.
- Testing different machine learning models (e.g., decision trees, SVMs) to improve prediction accuracy.

