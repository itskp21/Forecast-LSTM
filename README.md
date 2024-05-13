Made a Deep learning model, which could predict Google stock prices. Google Stock price dataset was obtained from YAHOO Finance.
Dataset included opening and closing prices of the last five years (December 2012 to December 2016). Before fitting the data to our model, it had to be preprocessed :

1. We have used Recurrent Neureal Network's LSTM model. LSTM Model works efficiently with scaled values of data, so it was scaled with MinMaxScaler using sklearn.preprocessing library.
2. The dataset was then split into training and test set with 80 % of data for training while 20 % for testing.
3. To feed the data to our model, we need to split the data into discrete values, i.e., features and values.
4. Since the LSTM model takes input a 3 Dimensional array, the 2 Dimension array was expanded to 3 Dimensions.
5. Optimizer used is ADAM and Loss function Used is Mean Squared error and used Dropuout Regularisation in Hidden Layers
