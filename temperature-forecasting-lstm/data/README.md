# Dataset Information for Temperature Forecasting using LSTM

This directory contains the dataset used for the temperature forecasting project utilizing Long Short-Term Memory (LSTM) networks.

## Dataset Source
The dataset is sourced from the Jena Climate dataset, which contains weather data collected from the Jena, Germany area from 2009 to 2016. The data can be accessed from the following link:
- [Jena Climate Dataset](https://storage.googleapis.com/tensorflow/tf-keras-datasets/jena_climate_2009_2016.csv.zip)

## Dataset Structure
The dataset consists of various meteorological measurements, including:
- Date and Time
- Temperature (in degrees Celsius)
- Pressure (in millibars)
- Humidity
- Wind Speed
- Other relevant weather parameters

The data is structured in a time series format, with each row representing a timestamp and its corresponding measurements.

## Preprocessing Steps
Before using the dataset for training the LSTM model, the following preprocessing steps were applied:
1. **Data Cleaning**: Removed any missing or erroneous entries.
2. **Sampling**: The dataset was downsampled to reduce the number of data points, retaining only every sixth entry to maintain a manageable size while preserving the temporal structure.
3. **Feature Engineering**: Additional features such as sine and cosine transformations of time were added to capture seasonal patterns.

## Usage
This dataset is used in the Jupyter notebook located in the `notebooks` directory. Ensure that the dataset is properly extracted and accessible for the notebook to function correctly.