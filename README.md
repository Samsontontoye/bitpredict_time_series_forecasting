## Time series forecasting in TensorFlow (BitPredict 💰📈)**
The goal of this notebook is to build a series of models in an attempt to predict the price of Bitcoin as at June 12th 2024

### What is a time series problem?

Time series problems deal with data over time.

Such as, the number of staff members in a company over 10-years, sales of computers for the past 5-years, electricity usage for the past 50-years.

The timeline can be short (seconds/minutes) or long (years/decades). And the problems you might investigate using can usually be broken down into two categories.

![example time series problems](https://raw.githubusercontent.com/mrdbourke/tensorflow-deep-learning/main/images/10-example-time-series-problems.png)

| Problem Type | Examples | Output |
| ----- | ----- | ----- |
| **Classification** | Anomaly detection, time series identification (where did this time series come from?) | Discrete (a label) |
| **Forecasting** | Predicting stock market prices, forecasting future demand for a product, stocking inventory requirements | Continuous (a number) |

In both cases above, a supervised learning approach is often used. Meaning, there are some example data and a label associated with that data.

For example, in forecasting the price of Bitcoin, the data could be the historical price of Bitcoin for the past month and the label could be today's price (the label can't be tomorrow's price because that's what's meant to be predicted).
