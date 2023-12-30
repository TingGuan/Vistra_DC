# Vistra_DC

## Introduction
This is a take-home data challenge on Vistra wind data.

## Data
The raw data is saved in `data` folder as Wind_data_copy.xlsx. Here we have two tabs, `Train` and `Target`.

In `Train`,
- **Column B (CF)** is the target variable, i.e., electricity output from corresponding wind farm.
- **Columns C - DJ** are independent variables, i.e., wind speed from different locations.

The task is to train a model using data in `Train` then make prediction for all records in `Predict`.
