# TPS7-Kaggle
Jupyter Notebooks for the Kaggle competition: Tabular Playground Series July 2021

<b>About the competition:</b>

The dataset is used for this competition is based on a real dataset, but has synthetic-generated aspects to it. The original dataset deals with predicting air pollution in a city via various input sensor values (e.g., a time series).

Type: Regression (3 target variables!)

Evaluation Metric: Root Mean Squared Log Error

<b>My repository contains the following notebooks:</b>

- tps7-interactive-eda-with-plotly.ipynb
    - EDA (Exploratory Data Analysis)
    - interactive visuals to analyse the variables
- tps7-tuned-xgb-graphic-validation.ipynb
    - feature creation
    - XGBoost
    - hyperparameter tuning with Optuna
 - tps7-don-t-ask-the-prophet.ipynb
    - feature creation
    - facebook's Prophet
  
  Note: it's very interesting to see how well (or better: bad) Prophet learns the training data compared to XGBoost
