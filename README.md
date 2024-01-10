#### Time Series Analysis Activity Guide
A. Data Exploration 
1. Descriptive Statistics: Calculate basic statistics for initial insights. 
2. Visualization: Create time series plots to observe trends and patterns.
B. Data Cleaning 
1. Date-Time Handling: Ensure proper formatting and sequencing of time-related data. 
2. Handling Missing Values: Discuss strategies for addressing missing time series data.
C. Time Series Modeling
##### A. Stationarity Check 
Time series is said to be stationary when its statistical properties, such as mean, variance, and autocorrelation, do not change over time.
The following are the 3 main components of stationarity:
i.	Constant Mean: The mean of the time series data should remain constant over time. This implies that, on average, the data points have a stable, unchanging central tendency.
ii.	Constant Variance: The variance (standard deviation) of the time series data should remain constant. The spread or dispersion of the data point should remain the same.
iii.	Constant Autocorrelation: Autocorrelation is the correlation of time series with its own past and future values. For a time series to be stationary the direction and strength of this correlation should be constant over time.

##### D. Model Selection 
1. Choose Time Series Model: Options include ARIMA, SARIMA, Exponential Smoothing, etc. 
●	ARIMA (AutoRegressive Integrated Moving Average): Combines autoregression, differencing, and a moving average to capture temporal dependencies. 
●	SARIMA (Seasonal ARIMA): Extends ARIMA to account for seasonal patterns in the data. 
●	Exponential Smoothing (ETS): Uses weighted averages of past observations to make predictions.
** Use the following links for implementation of the above three models:
https://medium.com/@shawanugya12/implementation-of-time-series-forecasting-methods-sarima-sarimax-and-prophet-ff8407b25aaa
https://towardsdatascience.com/time-series-in-python-exponential-smoothing-and-arima-processes-2c67f2a52788
2. Justification: Explain why the selected model is appropriate for the dataset.
#### D. Train-Test Split 
1. Divide the time series dataset into training and testing sets. 
2. Define the timeframe for training and testing.
####### E. Model Training and Evaluation 
1. Train the chosen time series model using the training dataset. 
2. Evaluate Model: Use appropriate metrics (e.g., Mean Squared Error, Root Mean Squared Error).
F. Apply the Trained Model 
1. Use the trained model to predict future values. 
2. Visualize Forecast: Plot predicted values against the actual time series.
##### G. Interpretation 
1. Analyze the forecasted results. 
2. Discuss any observed trends, seasonality, or anomalies.
##### H. Summary 
1. Summarize key findings from the time series analysis. 
2. Insights: Highlight any patterns or important information discovered through the analysis.
