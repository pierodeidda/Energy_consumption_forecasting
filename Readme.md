# Energy Consumption Forecasting with Classical and Recurrent Models

The project aims to develop an energy consumption forecasting system based on both classical (ARIMA/SARIMA) and deep learning (LSTM) time series analysis techniques. The model will support energy analysis and planning decisions by providing reliable forecasts of future consumption trends.

The work is designed to be applicable to real-world time series and includes exploratory time series analysis, statistical property testing, model training and comparison, and quantitative evaluation of predictive performance.

Use cases: an analyst needs to estimate energy consumption in the hours/days following the last available data to support procurement decisions on the energy market.

The system:
- produces short to medium-term forecasts with error estimates;
- compares the reliability of classical statistical approaches versus recurrent neural networks.

Business importance: Improved quality of quantitative forecasts, reduced exposure to decisions based on unmodeled data, and support for systematic strategy development.

Dataset
File: clustered\_hourly\_values\_all.csv (downloadable from the following link: https://github.com/Profession-AI/progetti-ml/blob/main/Previsione%20del%20Consumo%20Energetico%20con%20Modelli%20Classici%20e%20Ricorrenti/clusteredhourlyvalues_all.csv)

The dataset contains 30 hourly time series derived from the dataset collected in the "The Smart Metering Electricity Customer Behavior Trials (CBTs)" project. The dataset contains electricity consumption data between 2009 and 2010 for more than 5,000 homes, businesses, and other businesses in Ireland. Each time series in the clustered\_hourly\_values\_all.csv file represents the average consumption (kWh) of a cluster of users with similar profiles.
