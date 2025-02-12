# APPLYING MULTIPLE LINEAR REGRESSION (MLR) ON WEATHER IN SZEGED 2006-2016 USING PYTHON

In this project, I tried to apply multiple linear regression model on the **Weather in Szeged 2006-2016 dataset**, a comprehensive weather data for the city of Szeged, Hungary, over a ten-year period. This dataset is a valuable resource for understanding the historical weather patterns in Szeged and can be utilized for various analytical and predictive purposes.

**AIM**<br/>
The primary objective of this analysis is to develop a multiple linear regression model that can
accurately predict the apparent temperature based on other weather-related variables such as
humidity, wind speed, and visibility, air temperature, etc.

**Dataset Description**<br/>
It encompasses 96453, instances with 12 attributes.<br/>
- Date
- Summary
- PrecipType
- Temperature (C)
- Apparent Temperature (C)
- Humidity
- Wind Speed (km/h)
- Wind Bearing (degrees)
- Visibility (km)
- Loud Cover
- Pressure 
- Daily Summary

**Methodology**
- Data Preprocessing
- Feature Selection (Response and Predictor Variables)
Response Variable(Y) = Apparent Temperature<br/>
Predictor Variables(Xi’s) : X1 = Air Temperature<br/>
X2 = Humidity<br/>
X3 = Wind Speed<br/>
X4 = Visibility<br/>
X5 = Pressure<br/>
X6 = Encoded PrecipType<br/>
X7 = Encoded Summary<br/>
- MLR Assumptions Validation
- - Linearity Test Using Scatter plot of residuals
- - No Autocorrelation using Durbin-Watson Test
- - Homoscedasticity using Breusch-Pagan Test
- - Normality of Residuals using QQ Plot, Histogram of Residuals
- - No Multicollinearity using Correlation Matrix, Variance Inflation Factor(VIF)
- Model Adequacy using R-squared, Adjusted R-squared, MSE, RMSE, MAE