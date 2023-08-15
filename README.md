# Option Pricing 

The "data" part : there is 50ETF option and stock option data collected from the stock and fund market. The data is divided into training set and test set. "test_data_BS.py" is specially used for Black-Scholes model. 

The "core" part : files used for constructing the models and a single file for data processing.

The "main" part : applying the models and the data to predict option price, and compare their strengths and weaknesses through five measurements: MSE, RMSE, MAP, MAPE and PCC.
