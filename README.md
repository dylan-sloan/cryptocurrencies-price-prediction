# Top 10 Cryptocurrencies Price Predictions by Market Cap
A prediction model for the top 10 cryptocurrencies as of Feb. 2022, based on market cap. 
This is done using an LSTM neural network consisting of 200 neurons that uses the closing prices of each cryptocurrency.

The Top 10 Cryptocurrencies in question are, in order:

1. Bitcoin
2. Ethereum
3. Tether
4. Binance Coin
5. US Dollar Coin
6. Cardano
7. Solana
8. XRP
9. Terra
10. Polkadot

When the model is run on any given cryptocurrency, it uses cryptocompare.com's API to fetch the most up to date info on the crypto.

# Some Results
![image](https://user-images.githubusercontent.com/82912016/165632032-e85e4e68-6b6c-40f6-96c2-be5e23fa3cae.png)
![image](https://user-images.githubusercontent.com/82912016/165632095-2597d743-5ec3-4f83-ba49-4bdae97a3b83.png)

The above iteration of Bitcoin's model received an R2 score of 0.76.

# Disclaimer
This model was originally conceived through a baseline model by Abhinav Sagar. His model can be found here: https://github.com/abhinavsagar/Cryptocurrency-Price-Prediction

I improved on his model's results by playing with the hyperparameters, as well as expanding the model to other cryptocurrencies and using the most current data.
