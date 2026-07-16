
#ELECTRICITY DEMAND FORECASTING FOR GERMANY USING TIME SERIES MODELS


## Overview

This project investigates electricity demand forecasting for Germany using statistical, machine learning and deep learning models. The models are developed using the same training and testing period and compared using common forecasting evaluation metrics.


## Dataset

The project uses:

- Germany electricity demand data from Open Power System Data.
- Historical temperature data from the Open-Meteo API.



## Models Implemented

### Benchmark Models
- Mean Forecast
- Naive Forecast
- Seasonal Naive Forecast
- Drift Forecast

### Statistical Models
- SARIMA
- SARIMAX

### Machine Learning Model
- Gradient Boosting Regressor

### Deep Learning Model
- Long Short-Term Memory (LSTM)


## Project Workflow

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Stationarity testing
- Seasonal decomposition
- Benchmark forecasting
- SARIMA modelling
- SARIMAX modelling
- Gradient Boosting forecasting
- LSTM forecasting
- Model evaluation and comparison

---

## Evaluation Metrics

The forecasting models were evaluated using:

- RMSE
- MAE
- MAPE
- R² Score



## Repository Contents


| `Germany_Electricity_Demand_Forecasting.ipynb` | Complete notebook containing data preprocessing, model development and evaluation. |
| `best_sarima_results.csv` | SARIMA parameter combinations |
| `comparison_table.csv` *(if available)* | Final comparison of forecasting model performance. |
| `README.md` | Project overview and repository information. |


## Results

The LSTM model achieved the best forecasting performance with the lowest RMSE, MAE and MAPE values together with the highest R² value. The Seasonal Naive model remained a strong benchmark, while SARIMA, SARIMAX and Gradient Boosting produced reasonable forecasting results.


## Python Libraries

- pandas
- numpy
- matplotlib
- statsmodels
- scikit-learn
- tensorflow



## How to Run

1. Clone or download this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Install the required Python libraries.
4. Run the notebook from the beginning to reproduce the results.


## References

- Open Power System Data: https://data.open-power-system-data.org/time_series/
- Open-Meteo Historical Weather API: https://open-meteo.com/en/docs/historical-weather-api
- Box, G. E. P., Jenkins, G. M., & Reinsel, G. C. (2008). *Time Series Analysis: Forecasting and Control*. Wiley.



## Author

**Abinesh Boopal**

MSc Data Science

Time Series Modelling Coursework
