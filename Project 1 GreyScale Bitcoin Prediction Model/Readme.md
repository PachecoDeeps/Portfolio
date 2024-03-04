## Grayscale Bitcoin Trust (GBTC) Price Prediction Model

#### Introduction:
##### The increasing attention that cryptocurrency markets are receiving has led to the investigation of novel methods for predicting asset prices. A special investment opportunity is presented by the Grayscale Bitcoin Trust (GBTC), which gives investors exposure to Bitcoin without requiring them to buy or hold the cryptocurrency themselves. This paper presents a price prediction model for GBTC based on technical analysis indicators and historical data. Our goal is to improve prediction accuracy and offer insights into the dynamics of GBTC price movements by utilizing the power of LSTM neural networks.

#### Problem Statement:
##### Cryptocurrency markets are volatile and complex, making it very difficult to predict GBTC prices with any degree of accuracy using traditional methods. Traditional methods frequently miss the subtleties of market sentiment and fall short of identifying the fundamental patterns influencing price changes. Our goal is to create a reliable prediction model that uses cutting-edge modeling techniques and alternative datasets to increase forecasting accuracy and give investors insightful information.

### Methodology
#### Data Collection:
##### We used the Yahoo Finance API to access historical GBTC price information, including volume and the open, high, low, and close prices.

#### Data Preprocessing:
##### Created input sequences for training the LSTM model. Applied technical analysis indicators such as RSI and EMA. Scaled the data using Min-Max scaling.

#### Model Building:
##### To forecast time series, we used LSTM neural networks. We trained the model using historical data and assessed its performance with a variety of metrics.

#### Evaluation Metrics:
##### We used metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared (R2), and Mean Absolute Error (MAE) to evaluate the accuracy of the model.

#### Interpretation of Results:
##### We discussed the implications of our findings for market analysts and investors, as well as how the model performed.

#### Results
##### With an R2 score of 0.9626 on the test dataset, the LSTM model showed encouraging performance and strong explanatory power. The model also showed low RMSE and MAE, indicating that it could accurately predict GBTC prices. An analysis of the model's performance visually revealed that it closely matched real price movements, demonstrating how well it captured underlying trends.

#### Conclusion/Recommendations
##### In conclusion, using historical data and technical analysis indicators, the LSTM prediction model demonstrates potential for precise GBTC price forecasting. Predictive models should be used with caution and potential limitations in mind when making investment decisions, even though the model shows strong performance metrics. To further increase predictive accuracy, future research could concentrate on improving the model architecture, adding new features, and investigating different datasets.
