# Monthly Precipitation Forecasting with Prophet and SARIMA

This project uses historical monthly average precipitation data (from August 1939 to June 2024) to build and compare
two time series forecasting models: Facebook Prophet and SARIMA. The goal is to evaluate their performance and 
visualize forecasted precipitation over the next 12 months.

Data from the National Centers For Environmental Information website: https://www.ncei.noaa.gov

Data Link: https://www.ncei.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:US1TXDA0053/detail

The analysis includes:

* Data preprocessing with log transformation and differencing
* Modeling with Prophet, using log-differenced data and yearly seasonality
* Model diagnostics with residual plots and statistical tests
* Forecast generation for 13 future months
* Inverse transformation to interpret results on the original scale
* Comparison of Prophet vs. SARIMA forecasts using a visual plot

