# Flight Delay Prediction using Machine Learning

## Project Overview
This project predicts flight departure and arrival delays using historical aviation data.
It applies machine learning techniques to support airport and airline operational decision-making.

## Problem Statement
Flight delays impact passengers, airlines, and airport operations.
This project focuses on predicting:
- Departure Delay (DEP_DEL15)
- Arrival Delay (ARR_DEL15)

## Dataset
- Historical US flight operations data
- Features include flight timings, taxi times, congestion indicators, and turnaround metrics

## Feature Engineering
Key engineered features include:
- Turnaround Time
- Airport Congestion (hourly flight volume)
- Peak Hour Indicators
- Operational Stress Ratios

## Models Used
- CatBoost
- XGBoost
- Random Forest
- LightGBM

Tree-based models were selected due to their ability to handle non-linearity and complex interactions.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- AUC

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- CatBoost, XGBoost, LightGBM
- Google Colab

## Outcome
Arrival delays were found to be easier to predict than departure delays due to stronger operational stability after takeoff.

## Author
Akshara Yuvaraj  
MSc Data Analytics – Dublin Business School


