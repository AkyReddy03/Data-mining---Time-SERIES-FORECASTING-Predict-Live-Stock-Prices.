# Data-mining---Time-SERIES-FORECASTING-Predict-Live-Stock-Prices.
Time series ?
Time series forecasting is the process of analyzing time series data using statistics and modeling to make predictions and inform strategic decision-making.

Components of Time Series
-----------------------------------------------------------------------
Trend:
The trend shows the general tendency of the data to increase or decrease during a long period of time
Seasonal Variations:
These are the rhythmic forces which operate in a regular and periodic manner over a span of less than a year. 
Cyclic Variations:
The variations in a time series which operate themselves over a span of more than one year are the cyclic variations.
Random /Irregular Movements:
They are not regular variations and are purely random or irregular.

Introduction and problem specification
------------------------------------------------------------------------
Industry: The project is about predicting the prices of the live stocks using yahoo finance. The industry we are targeting is Finance and it is related to every company in the retail, banking, health-care, and logistics & transportation sectors.

WHY ?
A company's stock price reflects investor perception of its ability to earn and grow its profits in the future. 
Predicting stock prices is very important for finance practitioners to best allocate their assets and to academics to build better and more accurate asset pricing models. 
Predicting stock returns gives crucial implications about market efficiency.

Problem specification:
----------------------------------------------------------------------------
In this project, we are predicting whether the future price of a stock goes upward or downward (depicted as “Target”-(1/0)) based on past values of the data.
There are many websites predicting the stock prices. But they are predicting the stock prices of tomorrow based on today data. In my Knowledge, this is the first project where we are predicting the price of the stock change from minute to minute. 
Stock prices change from milli second to milli second based on situations happening around the world. That’s why it is important to develop a model that can help to predict the stock price from second to second. 
This is famous for the Intraday Traders.

Data Characteristics:
------------------------------------------------------------------------------

Independent Variables: DateTime, Stock Symbol, Company, Open, High, Close, Low, AdjClose, Volume.
Dependent Variable: Target
Model Type: Binary Classification

Data Models:
--------------------------------------------------------------------------------

This is a binary classification supervised problem; hence we used classification algorithms like Random forest, logistic regression algorithms, support vector machines.

Conclusion / Results:
---------------------------------------------------------------------------------
From the accuracy and confusion matrix, Logistic regression is the best classifier when compared to the random forest and Support vectors with 77% accuracy.
The model is telling that 77% of times the price of the stock goes up in the next second out of 100 times. Though it is not an accurate model, I would consider this as the better model.

Finding:
----------------------------------------------------------------------------------

For our analysis, we have taken the recent news that musk had officially took over the Twitter. We have recorded the change is price of the ‘TESLA’ when Elon musk bought the twitter on the 27- oct- 2022. 

Current Problem:
----------------------------------------------------------------------------------
Since there are random fluctuations in the stock price trend, it is hard to predict the exact value. 

Solution:
We have written a custom logic that used moving averages to predict the trend of the data. With the help of moving average, we used that data to create a model. If all the variables are held constant, then my model will be able to predict the future price of the data base don past and current data.

CEO Solution:
Using my model, CEO can predict the future price of the stock. This way investors can decide whether to invest in company or not.





