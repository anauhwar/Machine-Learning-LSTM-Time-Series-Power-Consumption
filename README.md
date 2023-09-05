# LSTM Time Series Power Consumption

## Introduction

This machine learning project focuses on analyzing and forecasting electric power consumption in a household using LSTM (Long Short-Term Memory) models. The dataset contains measurements of power consumption collected at a one-minute sampling rate over a period of nearly four years. Among the various electrical quantities and sub-metering values, our primary interest lies in the 'Global_active_power' variable.

## Objective

The main objectives of this project are as follows:

1. **Data Exploration**: Explore the provided dataset to gain insights into the power consumption trends and patterns over time.

2. **Data Preprocessing**: Prepare the data for modeling by cleaning, filtering, and selecting the relevant features, with a focus on 'Global_active_power.'

3. **LSTM Modeling**: Build LSTM (Long Short-Term Memory) time series forecasting models to predict future power consumption based on historical data.

4. **Statistical Normality Test**: Utilize statistical tests, specifically D’Agostino’s K^2 Test, to assess whether the power consumption data follows a Gaussian (normal) distribution.

## Statistical Normality Test

To ensure the accuracy and reliability of our time series forecasting models, we perform a statistical normality test on the 'Global_active_power' variable. D’Agostino’s K^2 Test is employed to evaluate whether the data distribution closely resembles a Gaussian distribution.

## Repository Structure

- `LSTM Time Series Power Consumption`: Jupyter notebooks detailing the data exploration, data preprocessing, LSTM modeling, and statistical tests.
- `README.md`: The main documentation file summarizing the project.

## Getting Started

To replicate this project or explore the analysis:

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/anauhwar/Machine-Learning-LSTM-Time-Series-Power-Consumption.git
   cd Machine-Learning-LSTM-Time-Series-Power-Consumption

## Conclusion
This project provides a comprehensive analysis of electric power consumption time series data and demonstrates the application of LSTM models for forecasting. Additionally, it assesses the normality of the data distribution, contributing to a more accurate understanding of power consumption trends.
