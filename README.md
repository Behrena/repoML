# TimeSeries prediction with LSTM Neural Network with (Keras and Pytorch)
# S&P 500 Stock Price Prediction 

1.  Detailed analysis of Stock prices as time-series data to find insights and findout best stocks among all the stocks

2.  Visualized stock prices and prove the hypothesis of daily return of stocks


3. Model evaluation metrics & performance comparison with RMSE & MAPE to measure accuracy of our model.

4. Analyize stocks historical data with Simple Moving average(SMA) & Exponential Moving average (EMA) techniques to predict stock movements.

   - Exponential Moving Average (EMA) is measuring trend direction over a period of time
   - SMA simply calculates an average of price data,

5. Apply ML algorithms & prepare stocks historical dataset for model training 

6.  LSTM (Long Short-Term Memory) Recurrent Neural network model of deep learning framework for time-series data for model training and predictions, 

- When evaluating a model's accuracy using RMSE (Root Mean Square Error) and MAPE (Mean Absolute Percentage Error), you are essentially comparing how far, on average, your model's predictions deviate from the actual values,

-  with RMSE giving more weight to larger errors due to its squared calculation, 
-  while MAPE expresses the error as a percentage of the actual value, making it useful for understanding relative error size across different scales; 

- a lower value in both metrics indicates a more accurate model


   **A lower RMSE indicates a better fit overall, while a lower MAPE means a smaller average percentage error.**



 7. ##### Evaluating the performance of a regression model

 - When evaluating the performance of a regression model, "accuracy" is not typically used as the primary metric, instead, 
 
 - Metrics like **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, **Mean Absolute Error (MAE)**, and **R-squared** are used to assess how closely the model's predictions align with the actual values, 
 
 - As regression models predict continuous values rather than discrete classifications where "accuracy" is more applicable; essentially,
 
 - You are measuring in regression how "close" the predictions are to the true values, not just whether they are "correct" or "incorrect" like in classification tasks. 

- Key points about evaluating regression models -  Regression metrics:
    
   1. Mean Squared Error (MSE): Calculates the average of the squared differences between predicted and actual values. 
   2. Root Mean Squared Error (RMSE): The square root of MSE, providing a more interpretable error value in the original unit of the data. 
   3. Mean Absolute Error (MAE): Calculates the average absolute difference between predicted and actual values, less sensitive to outliers than MSE. 

   4. R-squared (coefficient of determination): Represents the proportion of variance in the dependent variable explained by the independent variables. 

   #### Why use not accuracy in regression: 

   - Continuous values: Regression models predict continuous values, not discrete classes, so a simple "correct/incorrect" classification doesn't apply. 

   - Magnitude of error matters: In regression, the magnitude of the error is important, not just whether the prediction is "correct" or not