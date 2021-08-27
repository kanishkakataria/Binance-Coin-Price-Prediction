# Binance-Coin-Price-Prediction

*_Problem Statemen*t:- Develop a forecasting model for predicting the prices of Binance coin
Dataset Description: Binance coin is cryptocurrency by Binance. Binance is a cryptocurrency exchange that
provides a platform for trading various cryptocurrencies. It was founded in 2017 and is domiciled in the
Cayman Islands. Binance is currently the largest exchange in the world in terms of the daily trading
volume. Binance was founded by Changpeng Zhao.
Contains several parameters of daily prices of Litecoin. The data starts from 9-Nov 2017.
All the column descriptions are provided.

*_Model used :- Linear Regression*

*_Creation of the model:-*
I have imported the essential libraries and have read the dataset in a variable named coin.
Then I have done some pre -processing actions for churning and cleaning the data like I have created an additional column named Year which contains the year and the date column is removed permanently.I have also converted the volume column having currency data in form of M and K subscripts into numerical values for better calculation 
Visualised the data through different functions provided under matplotlib.pyplot and seaborn libraries.
The main task was of Training the dataset by splitting the dataset into training and test sets. During the analysis of the model I had dropped the unnecessary columns from the dataframe while training the model,performed residual error correction.Finally got an accuracy of 98% for the prediciton.

*_How to run the code:-*
The code can be run on jupyter notebook.





