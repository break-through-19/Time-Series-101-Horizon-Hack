# Time Series Forecasting
* If you're just getting started on exploring time-series forecasting this repository is for you.
* If you're looking for SOTA time-series forecasting techniques, this respository is for you as well.

## Time Series Data - Components [^1]
- **Trend** - Overall long term direction of the series like upward, downward, and horizontal.
- **Seasonality** - Repeated behaviour at regular intervals. Related to seasonal natural or human behaviour.
- **Cycles** - Cycles occur when there is an up and down pattern that is non-seasonal (that is, unpredictable and not  occurring at regular intervals). The length is varied. Difficult to detect than seasonality.
- **Irregularities** - Extreme dips and jumps in the time series.

## Evolution of Methods

### Statistical Models
- ARIMA (Auto Regressive Integrated Moving Average)
- ETS (Exponential Smoothing)
### Machine Learning
- XGBoost
- LightGBM

### Deep Learning
- Neural Networks based: LSTM, RNN
- Transformer based: [Chronos](https://github.com/break-through-19/chronos-forecasting), [TiDE](https://github.com/break-through-19/TiDE), [TimesFM](https://github.com/break-through-19/timesfm) 

## Interesting concepts:
- Black-Scholes-Merton Model - Used to predict Fair Value of an Options Contract. Suitable for European markets where Options can be executed only at expiry.
- The Greeks (Delta, Gamma, Theta, Vega) - Key parameters used in Risk Management

### References
[^1]: [What Is Time Series Forecasting?](https://youtu.be/VRX-KmgKXBw?si=ZXHe-67hS3E-mndN)
