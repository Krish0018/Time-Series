# Time-Series

### About the project
Worked of Reliance stock market data.
Used different techniques like AR, MA, models etc for the forecast of Reliance stck data.

### Tool Used
Used Python for data analysis for that particular dataset. Libraries used for this project are:
Numpy
Pandas
Matplotlib
Seaborn
adfuller
seasonal_decompose
acf, pacf
ARIMA


### Installation
for numpy
import numpy as np  

for Pandas
import pandas as pd

For Matplotlib
import matplotlib.pyplot as plt

For Seaborn
import seaborn as sns

For Adfuller
from statsmodels.tsa.stattools import adfuller

For seasonal_decompose
from statsmodels.tsa.seasonal import seasonal_decompose

For ACF, PACF
from statsmodels.tsa.stattools import acf, pacf

For ARIMA
from statsmodels.tsa.arima_model import ARIMA

### Key Insights
Finding the rolling mean and standard deviation from the data we got after logscaled data minus moving average

<img width="491" alt="ma" src="https://user-images.githubusercontent.com/69238621/140741199-7821a183-ed48-4155-9b2c-84a8a0992817.PNG">

Checking the data, trend and seasonality with seasonal decomposition after rejecting the null hypothesis.

<img width="522" alt="seas" src="https://user-images.githubusercontent.com/69238621/140743670-32e97e2c-ada1-42e7-889b-01f237a37878.PNG">

Forecasting using ARIMA model for next 50 days.

<img width="286" alt="fore" src="https://user-images.githubusercontent.com/69238621/140744115-cd1bba54-7d45-4f33-9569-038aa44c1c4e.PNG">

