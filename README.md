# Heart Disease Prediction Project

## Overview
This project aims to predict the presence of heart disease using the Hungarian subset of the UCI Heart Disease dataset. We focus on three key predictors: age, cholesterol levels, and maximum heart rate. The goal is to determine the effectiveness of these predictors in forecasting heart disease using a k-nearest neighbors (KNN) classification model.

## Dataset
- **Source:** UCI Heart Disease dataset (Hungarian subset)
- **Features Used:** Age, Cholesterol, Maximum Heart Rate
- **Target:** Presence of Heart Disease

## Methodology
1. **Data Preprocessing:**
   - Cleaned the dataset by replacing missing values and converting data types.
   - Split the data into training (75%) and testing (25%) sets.

2. **Model Development:**
   - Standardized the data.
   - Applied k-nearest neighbors (KNN) classification.
   - Used cross-validation to determine the optimal number of neighbors (k).

3. **Model Evaluation:**
   - Evaluated the model on the test set using accuracy, precision, recall, and confusion matrix.

## Results
- **Optimal k:** 13
- **Accuracy:** 65.2%
- **Precision:** 68.6%
- **Recall:** 81.4%

## Dependencies
- R
- Libraries: tidyverse, repr, tidymodels, gridExtra, cowplot

## How to Run
Open the provided R file "project_report.ipynb".

## References
- Di Cesare M, et al. (2024). The Heart of the World. Glob Heart.
- Harvard Health. (2023). What is a normal heart rate?
- Janosi, A., et al. (1988). Heart Disease. UCI Machine Learning Repository.
- Rodgers JL, et al. (2019). Cardiovascular Risks Associated with Gender and Aging. J Cardiovasc Dev Dis.
