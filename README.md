# Natural-Gas-Forecast-Model-R
52 week forecast model in R for natural gas prices, total volume and weekly change in inventory. 

Comes with robust set of visualizations.

Core functionality is an ensemble of 3 approaches:
1) Exponential smoothing to weight in seasonality
2) ARIMA model to weight towards a regressive approach to patterns in the time series
3) Neural Netowrk model to abstract complex relationships between variables. 

Each model for each variable is averaged. There are 9 forecast models and one model that consilidates results for final output. 

The base data set is a simple data frame of natural gas weekly prices, weekly total volume in storage and weekly change in inventory. 
The data set starts on 1/08/10. All three values are represented as a column and the rows are each eekly value from 1/08/10 to present. 
