# LSTM Stock Market Predictor
Predicts stock prices based on previous history using the Long Short-Term Memory model

## Dependencies:
`tensorflow.compat.v1`: 

This was developed on an AMD Radeon RX580. The normal tensorflow library does not support AMD GPUs, so this project uses an experimental version of tensorflow instead



## How to Use:
Simply run the jupyter notebook `Stock Price Predictor.ipynb`.

To try out different stocks, download from Yahoo Finance using the instructions below
1. Go to a company's stock page and click on historical data. 
2. Select the desired time frame
3. Click download ot get the CSV file.
4. Change the path in `Stock Price Predictor.ipynb` to use your stock CSV file. 

### Potential Improvement: 

Use the Yahoo Finance library to download any stock's history easier and better
