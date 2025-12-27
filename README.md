# Time Series Forecasting in Finance
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

## Interesting Monetization Strategies
### Arbitrage
- Arbitrage is the practice of profiting from temporary price differences for the same asset in different markets by buying it cheap in one and selling it high in another, essentially locking in low-risk gains by exploiting market inefficiencies.
- Variants include spatial (as explained in previous point), triangular (currencies), and merger arbitrage.

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/b14b8682-3374-48ff-8720-ce3b88fb3bf3" />

### Statiscal Arbitrage
- Statistical arbitrage (often called "stat arb") is a highly quantitative and computationally intensive trading strategy that uses statistical models to identify and profit from temporary pricing inefficiencies in a large number of financial assets.
- The core principle of statistical arbitrage is **mean reversion**, the theory that prices and returns eventually move back towards their historical averages or expected values. 

### Pairs Trading (Mean Reversion)

### 

## Notable Experts & Pioneers
- [Thomas Peterffy](https://www.forbes.com/profile/thomas-peterffy/)
- Jim Simons - Renaissance Tech
- Harry Markowitz - The Modern Portfolio Theory

## Readworthy Articles
- [History of Algorithmic Trading - 17th to 21st century](https://analyzingalpha.com/algorithmic-trading-history)
- [How Harry Markowitz Revolutionized Investing with Modern Portfolio Theory](https://www.investopedia.com/terms/h/harrymarkowitz.asp)


#### References
[^1]: [What Is Time Series Forecasting?](https://youtu.be/VRX-KmgKXBw?si=ZXHe-67hS3E-mndN)
[^2]: [What is Arbitrage?](https://www.investopedia.com/terms/a/arbitrage.asp#toc-what-is-arbitrage)
