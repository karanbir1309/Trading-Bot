
# TRADING BOT USING MACHINE LEARNING

This project combines technical and sentiment analysis of financial news using the FinBERT model with an automated trading strategy implemented using the Alpaca API. The goal is to leverage sentiment insights to make trading decisions for a specified asset, such as the SPY ETF.
You'll need to set up an Alpaca paper trading account and obtain API credentials (API_KEY and API_SECRET). Update API_KEY and API_SECRET in the MLTrader class to link to your Alpaca account



## TECHNOLOGIES USED
Python: Programming language used for implementation.

Transformers Library: Used for leveraging pre-trained transformer models like FinBERT.

PyTorch: Deep learning framework used for model training and inference.

Alpaca API: Provides access to financial market data and enables trading functionalities.

YahooDataBacktesting: Conducts backtesting to evaluate strategy performance over historical data.
## USAGE
1. Sentiment Analysis: Utilizes the FinBERT model to classify news sentiment into categories: positive, negative, or neutral.

2. Automated Trading: Executes buy or sell orders on the SPY ETF based on sentiment analysis results.

3. Backtesting: Validates the strategy's performance using historical data
## EXAMLE OUTPUT
After running the code, you will see trading decisions printed to the console based on the sentiment analysis.
## FUTURE DEVELOPMENTS
1. Real-time Data: Enhance trading strategy to operate in   real-time with live data feeds.
2. UI Integration: Develop a user-friendly interface for strategy monitoring and configuration adjustments.
## MADE BY
1.AMISHI BHAMRA

2.KARANBIR SINGH PAHWA
