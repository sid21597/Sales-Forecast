# Sales-Forecast
Extracted the data from file and convert it into Data Frame
Find the null values and imputed them using random sampling
Grouped the dataframe by year and product lines over counting the sales
Sliced the year and encoded it ordinally
Grouped months into quarters and encoded them ordinally
One hot encoded the product line features
Used XGBRegressor and Random Forest Regressors
Predicted only on Quarter and year for setting a baseline
Then, predicted also on product line and compared the results
Baseline MAPE = 0.295 for XGBRegressor
Actual model MAPE = 0.095 for XGBRegressor
