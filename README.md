# Climate Change Prediction

A machine learning project for predicting **land surface temperature in Egypt** using historical hourly ERA5 climate data.

## Overview

This project explores whether traditional machine learning models can learn relationships between meteorological variables and land surface temperature.

The workflow includes:

* ERA5 climate data preprocessing
* Time-based feature engineering
* Wind speed and direction calculation
* Exploratory data analysis
* Comparison of Linear Regression, Random Forest, and XGBoost
* Random Forest hyperparameter tuning
* Model evaluation using MAE, RMSE, and R²

## Results

The **Random Forest Regressor** achieved the best overall performance on the held-out test period:

| Metric | Tuned Random Forest |
| ------ | ------------------: |
| R²     |               0.907 |
| MAE    |               1.752 |
| RMSE   |               2.293 |

The model selection and analysis also examine feature importance and prediction behavior over time.


## Data

The project uses **hourly ERA5 climate data** covering a location in Giza, Egypt, from 2000 to 2025.

The raw dataset is not included in this repository. See `data/README.md` for dataset information.

## Documentation

For the complete methodology, preprocessing decisions, experiments, results, limitations, and discussion, see:

**`reports/land_surface_temperature_prediction_report.pdf`**

## Technologies

Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · XGBoost · Jupyter Notebook
