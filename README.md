# King County House Price Prediction

## Project Overview
This project analyzes house prices in King County (including Seattle) from May 2014 to May 2015. We explore key factors influencing prices and build predictive models.

## Data Processing
- Removed unimportant columns with no impact on the target value (`price`)
- Converted `date` column to datetime format.
- Created new features: `age` (house age) and `was_renovated` (binary indicator).

## Exploratory Data Analysis
- Visualized price distribution and correlation between features.
- Identifiedand explored high-value properties ($650K+) for deeper insights.

## Machine Learning Model
- Used several well-known ML models to predict house prices.
- Standardized numerical features.
- Explored various feature engineering scenarios.
- Evaluated model performance using `MAE`, `RMSE`, and `R²`.

## Results
- Top 10 important features were explored.
- Achieved competitive predictive accuracy (e.g. R² = 0.86 in case of Random Forest Regressor)
- Slight improvement of accuracy and prediction measures over baseline case.
