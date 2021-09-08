# Stock-Market-Prediction-And-Forecasting-Using-LSTM
One method for predicting stock prices is using a long short-term memory neural network (LSTM) for times series forecasting.
We’ll use a combination of AI calculations to forecast this company’s future stock price with LSTM.

# Execution Process
### 1. Loading the Data
The Appl data is from 2015-05-27 up to 22-05-2020. We take the **close** column for the stock prediction. We can use the same strategy.

![data](https://user-images.githubusercontent.com/59818604/132550808-de828f36-f1f5-4143-8990-26aa8b55e0a0.png)

![Data_plot](https://user-images.githubusercontent.com/59818604/132552038-7d479ef9-4fd9-49af-9100-15c4ebc59cce.png)

### 2. Train and Test Split
The training size should be 65% of the total length of the data frame, the test size should be the difference between the length of the dataset and the training size.
### 3. Data Preprocessing
Now the timestep value will be 100. We split the data X, Y. In the 0th iteration the first 100 elements goes as your first record and the 101 elements will be put up in the X. The 100 elements will be put up in the Y.
### 4. LSTM has three gates:
The input gate: The input gate adds information to the cell state,
The forget gate: It removes the information that is no longer required by the model,
The output gate: Output Gate at LSTM selects the information to be shown as output.

![model](https://user-images.githubusercontent.com/59818604/132559522-8eb5ab89-32fe-4214-933c-f420855fc22c.png)

### 5. Prediction
The values in train predict and test predict. I got,i am just plotting it:
A. Green indicates the Predicted Data
B. Blue indicates the Complete Data
C. Orange indicates the Train Data

![Prediction](https://user-images.githubusercontent.com/59818604/132559563-c0747f26-7bec-497f-a2ea-83e7c8c93ef9.png)

# References
[link to Google!](https://github.com/mwitiderrick/stockprice)


