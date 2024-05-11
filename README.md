# Rainfall-Forecasting-Model-using-ARIMA.
Use manual ARIMA and Auto ARIMA models to forecast and evaluate model . By Comparison these two models use the best model to do the future rainfall at western province in Sri Lanka.
## Introduction:

The development of a machine learning model for rainfall prediction. The model utilizes time series analysis techniques to analyze historical rainfall data and forecast future rainfall amounts.

## Data Analysis:

The initial step involved assessing the stationarity of the time series data, a crucial aspect for accurate forecasting. Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots were employed to visually identify any patterns or trends in the data. The Augmented Dickey-Fuller (ADF) test was subsequently conducted to statistically confirm stationarity. A highly significant p-value (less than 0.05) indicated rejection of the null hypothesis (data has a unit root) and confirmed stationarity of the data.

## Model Selection:

We evaluated various ARIMA (Autoregressive Integrated Moving Average) models to determine the most suitable one for our rainfall prediction task. Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) were employed as the primary evaluation metrics. The ARIMA(2,0,0) model emerged as the optimal choice based on achieving the lowest MSE and RMSE values.

## Model Evaluation:

The chosen ARIMA(2,0,0) model was trained and evaluated on the test data. Specific performance metrics relevant to rainfall prediction (e.g., MSE, RMSE, MAE, MAPE) were employed to assess its effectiveness. Additionally, visualization techniques, such as plotting predicted versus actual rainfall values, can be incorporated to provide a clearer picture of the model's behavior.

## Conclusion:

This project successfully developed a time series-based ARIMA(2,0,0) model for rainfall prediction. The model demonstrates the potential of machine learning techniques for analyzing historical rainfall patterns and forecasting future rainfall amounts.

## Future Work:

Evaluating more advanced time series models (e.g., SARIMA, LSTM) for potentially improved performance.
Incorporating additional weather data (e.g., temperature, humidity) to enhance the model's prediction capabilities.
Fine-tuning the hyperparameters of the ARIMA model to potentially optimize its performance.
This report provides a concise overview of the rainfall prediction model's development process, highlighting the key steps of data analysis, model selection, and evaluation. By incorporating further exploration and refinements, the model's accuracy and effectiveness in forecasting rainfall patterns can be continually improved.
