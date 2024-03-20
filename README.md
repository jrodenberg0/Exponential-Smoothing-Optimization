# About 

This function was created to forecast using Holt-Winters Exponential Smoothing. It uses Level, Trend and Seasonality to predict future sales. Exponential Smoothing is a tried and true time-series model, very well suited for supply chain forecasting.

I built this to take in your series, seasonal periodicity, specifying multiplicative or additive trend, and specifying the number of splits via Time Series Cross Validation.

** Please note that n_splits must be only 2 if you do not have more than 2 seasonal cycles.** 

The optimization function searches over a predefined coarse grid to find the optimal alpha, beta, gamma coefficients on the train series, 

The model returned is fully fit using the optimal params (minimizing the Mean Absolute Error).

In the future, I would like to add more robust cross validation to this workflow. 

Thanks for reading! 

Jack
