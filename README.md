# City of Chicago Energy Forecasting

This repository contains a project focused on energy forecasting for the City of Chicago, leveraging advanced data analysis and machine learning techniques to predict energy usage patterns. The goal is to provide insights into energy consumption trends, enabling smarter energy management and sustainability initiatives.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Approach](#approach)
- [Modeling Techniques](#modeling-techniques)
- [Results](#results)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)
- [Contributions](#contributions)

## Introduction

Energy forecasting is crucial for efficient energy management and urban planning. This project explores energy consumption patterns in Chicago, creating predictive models to enhance understanding and future planning.

## Dataset

The dataset for this project is sourced from [City of Chicago Open Data Portal](https://data.cityofchicago.org/) and contains historical energy usage data, weather conditions, and other relevant metrics. Ensure that the datasets are downloaded and stored in the following directory:

### Features:
- **Energy Usage**: Hourly energy consumption metrics.
- **Weather Data**: Temperature, humidity, and precipitation data.
- **Temporal Features**: Year, month, day, and hour.

### Add Dataset
Download the datasets and place them in the `data/` directory as specified above before running the analysis.

## Approach

1. **Data Preprocessing**:
   - Cleaned the raw data for missing and inconsistent values.
   - Performed feature engineering to extract meaningful predictors.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized energy trends and correlations.
3. **Model Development**:
   - Built and trained machine learning models to forecast energy usage.

## Modeling Techniques

This project employs the following machine learning algorithms:
- **Linear Regression**: For baseline predictions.
- **Random Forest Regressor**: To capture non-linear relationships.
- **XGBoost**: For high-accuracy predictions with fine-tuning.

Hyperparameter optimization was performed to enhance model performance.

## Results

The models achieved promising results, demonstrating accuracy improvements over baseline approaches. Evaluation metrics such as RMSE and MAE were used to validate the models.

## How to Use

### Prerequisites
- Python 3.8 or later
- Jupyter Notebook

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/DhyanVGowda/City-of-Chicago-Energy-Forecasting.git
   cd City-of-Chicago-Energy-Forecasting

2.Install dependencies:
## Dependencies

The project requires the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

3. Add the datasets to the `data/` folder as specified above.

4. Open the Jupyter Notebook to explore the analysis and predictions:
   ```bash
   jupyter notebook Chicago_Energy_Prediction.ipynb

## Contributions

Contributions are welcome! Please feel free to submit issues or pull requests for enhancements or fixes.

### Note

This project is currently under development and will incorporate **AutoGen** for advanced automation and enhancements.

