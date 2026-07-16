
## ELECTRICITY DEMAND FORECASTING FOR GERMANY USING TIME SERIES MODELS


## OVERVIEW
Electricity demand forecasting is an important task for power system operation and energy management. Accurate forecasts help electricity providers plan power generation, schedule available resources, maintain grid stability and support future operational planning while reducing unnecessary operating costs.

In this project, historical Germany electricity demand data is analysed to investigate how different forecasting techniques perform on the same dataset. The analysis includes data preparation, exploratory data analysis, the use of temperature-based predictor variables where appropriate, and the development of several forecasting models.

The models developed in this notebook include benchmark forecasting methods, SARIMA, SARIMAX, Gradient Boosting Regression and a Long Short-Term Memory (LSTM) neural network. Weekly data is used for the statistical and machine learning models, while hourly electricity demand data is used for the LSTM model.

The forecasting performance of each model is evaluated using RMSE, MAE, MAPE and R². The results are then compared to determine which forecasting approach provides the best balance between forecasting accuracy, model complexity and practical use for electricity demand forecasting.



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


## Evaluation Metrics

The forecasting models were evaluated using:

- RMSE
- MAE
- MAPE
- R² Score



## Repository Contents
| File | Description |
|------|-------------|
| `Germany_Electricity_Demand_Forecasting.ipynb` | Complete notebook containing data preprocessing, model development and evaluation. |
| `best_sarima_results.csv` | SARIMA parameter combinations with their corresponding AIC and BIC values used during model selection. |
| `README.md` | Project overview, repository structure and instructions for running the notebook. 



## Results

The LSTM model achieved the best forecasting performance with the lowest RMSE, MAE and MAPE values together with the highest R² value. The Seasonal Naive model remained a strong benchmark, while SARIMA, SARIMAX and Gradient Boosting produced reasonable forecasting results.


## Python Libraries
• Pandas
• NumPy
• Matplotlib
• Seaborn
• SciPy
• Statsmodels
• Scikit-learn
• TensorFlow / Keras
• itertools
• math
• warnings



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
