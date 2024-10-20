# Predicting Hurricane Categories Using Machine Learning

## UNC MADS DATA780 Project

### Authors:
- **Hubert Hwang**
- **Sooji Rhodes**

---

## Project Overview

This project aims to predict the category of hurricanes using machine learning techniques, based on meteorological data sourced from NOAA’s Atlantic Hurricane Database (HURDAT2). The model will analyze key features such as wind speed, pressure, and storm position to predict the intensity category of hurricanes, offering insights for improved disaster preparedness.

---

## Objective

The goal is to build a machine learning model that can accurately predict hurricane categories ranging from tropical depressions to Category 5 hurricanes. By leveraging both tabular and sequential data, we explore traditional methods like Random Forest and Gradient Boosting, as well as advanced methods such as Artificial Neural Networks (ANNs) and Recurrent Neural Networks (RNNs/LSTMs) to capture storm dynamics.

---

## Dataset

The dataset used in this project is the [NOAA Atlantic Hurricane Database (HURDAT2)](https://www.nhc.noaa.gov/data/hurdat/hurdat2-1851-2023-051124.txt), which contains historical information on hurricanes and tropical storms in the Atlantic from 1851 to 2023. Detailed documentation on the dataset format can be found [here](https://www.nhc.noaa.gov/data/hurdat/hurdat2-format-atl-1851-2021.pdf).

---

## Key Features

- **Timestamps**: Six-hourly observations of hurricanes, including position and meteorological attributes.
- **Wind Speed**: A key feature for determining hurricane strength.
- **Pressure**: Minimum pressure readings, another indicator of storm intensity.
- **Geographic Position**: Latitude and longitude of storms over time.

---

## Methods

We are utilizing several machine learning models to predict hurricane categories:

1. **Random Forest**: A robust ensemble method well-suited for tabular data.
2. **Gradient Boosting**: Sequential decision trees to handle complex, non-linear relationships.
3. **Artificial Neural Networks (ANNs)**: For complex, non-linear data patterns.
4. **Recurrent Neural Networks (RNNs/LSTMs)**: To capture the temporal evolution of storms using sequential data.

---

## Evaluation Metrics

We will evaluate the performance of our models based on:

- **Accuracy**
- **Confusion Matrix**
- **Precision, Recall, and F1-Score** (to assess the balance between classes)
- **ROC-AUC** (for overall performance across categories)

---

## Project Timeline

| **Task**                                      | **Deadline**        |
|-----------------------------------------------|---------------------|
| Data Collection and Preprocessing             | Week 1              |
| Feature Engineering and Data Aggregation      | Week 1              |
| Model Training (Random Forest, Gradient Boosting) | Week 2              |
| Model Training (ANNs and LSTMs)               | Week 3              |
| Model Evaluation and Hyperparameter Tuning    | Week 4              |
| Final Presentation and Report                 | End of Week 4       |

---

## Repository Structure

```bash
├── data/                   # Dataset and preprocessed data
├── notebooks/              # Jupyter Notebooks for analysis and model training
├── src/                    # Source code for models and preprocessing scripts
├── README.md               # Project overview and setup instructions
└── results/                # Model performance results and final reports