# FbProphet Time Series Forecasting

## Overview
This project involves building a time series forecasting model using FbProphet for airline passenger data. The goal is to predict future passenger counts based on historical trends.

## Requirements
- Python 3
- Libraries: pandas, fbprophet, matplotlib

## Setup
Install required libraries:
   ```bash
   pip install pystan
   conda install -c conda-forge fbprophet
   ```

1. Clone the repository:
```bash
   git clone https://github.com/subhan-liaqat/Time-Series-Forecasting-with-FBProphet
   ```

2. Run the Jupyter notebook:
```bash
jupyter notebook
```

## Project Structure
airline_passengers.csv: Dataset containing historical airline passenger counts.
FbProphet_Forecasting.ipynb: Jupyter notebook with the code for data preprocessing, model training, and analysis.

## Steps
Open the Jupyter notebook fbprophet.ipynb.
Follow the step-by-step instructions for:

Installing required libraries.
Loading and exploring the dataset.
Cleaning and preprocessing the data.
Training the FbProphet model.
Making future projections and visualizing results.
Conducting time series analysis and cross-validation.

## Results
The notebook includes visualizations of predicted projections and model components.
Time series analysis is conducted for the years 1960-1962.
Cross-validation metrics, such as RMSE, are used to assess model performance.
