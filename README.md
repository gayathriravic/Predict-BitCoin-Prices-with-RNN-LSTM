# Predict-BitCoin-Prices-with-RNN-LSTM

I have used historical data from www.coinmarketcap.com . I get the daily price for BitCoin and Ethereum.

Data Processing:
```
1. Remove any missing values from the dataframe.
2. Convert string to numeric values.
3. Merge dataframes.
4. Removing unnecessary columns. (Feature Selection)
5. Sorting data based on most recent date.
6. Splitting data into train and test sets.

```

I also calculate bitcoin volatality and change in prices.

LSTM
```
Used 3 layers of LSTM with 512 Neurons followed by a dropout factor of 0.25

‘tanh’ for activation function and Mean Squared Error for loss function.

```
