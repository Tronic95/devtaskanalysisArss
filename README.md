
# Task Delivery Analysis by Muhammad Arss

This repository contains the data analysis, machine learning modelling, and insights for delivery task data.

## View Analysis Report

[Click here to view the Task Delivery Analysis HTML report](https://rpubs.com/fitraArss/DevTaskAnalysis)


## Project Overview
- **Objective:** Identify key factors influencing COD (Cash on Delivery) success and build a predictive model to support operational optimisation.
- **Data:** 10-day sample delivery task data in JSON format.
- **Key Result:** Random Forest model with **AUC 0.9959**, highlighting route, courier, and delivery time as main drivers of COD success.

## How to Run
1. Clone this repository.
2. Install required packages listed in `requirements.txt`.
3. Open and review the analysis results in the HTML report.

## Analysis & Modelling
- Data cleaning and feature engineering (datetime parsing, route creation, task duration calculation).
- Random Forest modelling with hyperparameter tuning using H2O.
- Variable importance and SHAP analysis for business insights.
- Recommendations to improve operational efficiency and courier performance.

## Author
**Muhammad Nachnoer Novatron Arss**