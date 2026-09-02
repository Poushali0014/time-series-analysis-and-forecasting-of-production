# time-series-analysis-and-forecasting-of-production
**Time Series Analysis and Forecasting of Monthly Federal Reserve Board Production Index**

📌 **Project Overview**

This project focuses on the time series analysis and forecasting of the Monthly Federal Reserve Board Production Index. The objective is to analyze the underlying temporal patterns in the production index and develop a suitable forecasting model for future values.

🎯 **Objectives**

💠To observe the time series plot of the production data  recorded month-wise and 
understanding the underlying pattern, components in the data. 

💠To fit appropriate model to the residual series after removing the deterministic 
components from the data. 

💠To forecast production index for future timepoints and checking whether the 
forecasts generated are aligned with the original data.

🛠️ **Tools and Technologies**

R-Studio

**R Packages**

💠forecast

💠tseries

📊 **Methodology**

The project follows the following workflow:

💠Visualizing the time series plot of 'prodn' dataset from 'astsa' package in R.

💠Checking the stationarity of the data.

💠Identifying suitable choices ofthe parameters of SARIMA model from the ACF and PACF plot of detrended, de-seasonalized series.

💠Fitting candidate SARIMA models and comparing them with respect to AIC values.

💠Generating forecasts for the future periods and visualizing them along with historical observations.

👩‍💻 **Author**

Poushali Dutta
