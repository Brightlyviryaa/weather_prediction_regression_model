# Weather Data Preprocessing and Model

## Project Overview

This project aims to preprocess a historical weather dataset (`weatherHistory.csv`) for machine learning model development. The dataset contains various meteorological features, including temperature, humidity, wind speed, and visibility, among others. The goal is to prepare the data for training and testing a weather prediction model, with 10% of the latest data used for testing.

## Team members

This is our team member dedicated to work on this project.

| Nama               | NIM          |
| ------------------ | ------------ |
| Brightly Virya | 00000068227 |
| Batara Hotdo Horas Simbolon | 00000078626 |
| Daniel Isaach Hatuaon Siregar | 00000078609 |
| Christopher Alvaro Maria Samola | 00000073214 |

## Dataset

The dataset used in this project is `weatherHistory.csv`, which includes the following columns:

- `Formatted Date`: The date and time of the weather observation.
- `Summary`: A brief summary of the weather.
- `Precip Type`: The type of precipitation (e.g., rain, snow).
- `Temperature (C)`: The temperature in degrees Celsius.
- `Apparent Temperature (C)`: The apparent or "feels like" temperature.
- `Humidity`: The humidity level (0 to 1).
- `Wind Speed (km/h)`: The wind speed in kilometers per hour.
- `Wind Bearing (degrees)`: The direction the wind is coming from, in degrees.
- `Visibility (km)`: The visibility in kilometers.
- `Loud Cover`: Cloud cover measurement.
- `Pressure (millibars)`: Atmospheric pressure in millibars.
- `Daily Summary`: A detailed summary of the daily weather.

## Features

This project includes the following features:

- **Preprocessing the dataset**: Convert the `Formatted Date` to a datetime format, and sort the data chronologically.
- **Data splitting**: Split the dataset into training and testing sets, with the latest 10% of the data used for testing.
- **Category identification**: Extract and display the unique categories present in the `Summary` and `Precip Type` columns.

## Model

The model is intended to predict the **Percip type** based on other meteorological features. Specifically:

- **X (Features)**: The input features used for the prediction model will be the following columns: `Humidity`
- **y (Target)**: The target variable to be predicted is the `Percip type` column.
- **Prediction**: The model aims to predict the actual temperature based on other features in the dataset.

## Requirements

To run the code in this project, you need to have the following dependencies installed:

- Python 3.x
- Pandas (for data manipulation)
- Scikit-learn (for model development)
- Jupyter Notebook (for interactive data analysis)

You can install the required Python libraries using `pip`:

```bash
pip install pandas scikit-learn jupyter
```
