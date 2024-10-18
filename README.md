# DATA780_Final_Project
Repository for the final project in UNC MADS DATA780

# Predicting Hurricane Categories Using Machine Learning

## Authors:
- **Hubert Hwang**
- **Sooji Rhodes**

## Project Overview:
This project aims to predict the category of hurricanes based on historical data from the NOAA Atlantic Hurricane Database (HURDAT2), covering storms from 1975 to 2021. By using machine learning models, we aim to improve hurricane prediction to assist in better disaster preparedness and response.

## Dataset:
We are using the [NOAA Atlantic Hurricane Dataset](https://www.kaggle.com/datasets/utkarshx27/noaa-atlantic-hurricane-database/data). Key features include:
- **Wind speed, pressure, position, and storm type**, measured every six hours.
- **Target variable**: Hurricane category (0 to 5).

## Methodology:
- **Data Preprocessing**: Handling missing data and feature engineering for meteorological features.
- **Machine Learning Models**: 
  - Random Forests (Scikit-learn)
  - Gradient Boosting (Scikit-learn)
  - Artificial Neural Networks (TensorFlow)
  - Recurrent Neural Networks (LSTMs in TensorFlow)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

https://www.nhc.noaa.gov/data/hurdat/hurdat2-format-atl-1851-2021.pdf
https://www.nhc.noaa.gov/data/hurdat/hurdat2-1851-2023-051124.txt
