# Stock Market Prediction of the Short-term Impact of Trump's Tweets

Social media makes the spreading of news faster and broader, but at the same time, brings volatility to the stock market. Making predictions on the news events and react quickly gives comparative advantage in making more profits or reduce losses. 

In this project, we try to understand and predict the impact of a very special kind of news, tweets from President Trump, which has become the most uncertainty in the market. We try to model the market’s reaction to his tweets in the short term using supervised learning. 

We tried two different models, Linear regression and Long Short Term Memory Recurrent Neural Network (LSTM), to predict the reaction of the market (rise / fall / stays the same) over a certain time after Trump makes a tweet. Each model have different training samples. Training samples for the Linear Regression are bags of words with each entry representing a tweet. Samples for LSTM are a transformation of his tweets into a sequence of vectors that represents each word (or subword). Labels are variations in the trading price of the ETF after a certain time frame.


## Run the project

Run the notebook with latest version of Jupyter Notebook and Python. Recommend using Anaconda to install dependencies. 

## Report
* [Report PDF](https://github.com/Jiaxuan-Ren/Trump-tweet-stock-market/blob/master/Stock%20market%20prediction.pdf)

## Built With

* [Python](https://www.python.org)
* [Jupyter Notebook](https://jupyter.org)
* [Anaconda](https://www.anaconda.com)
* [Wharton Research Data Services](https://wrds-www.wharton.upenn.edu) - NYSE Trade and Quote
* [TrumpTwitterArchive](http://www.trumptwitterarchive.com) - Archive of Trump's tweets

## Authors

* **Jiaxuan Ren** - [Jiaxuan-Ren](https://github.com/Jiaxuan-Ren)
* **Kaihan Zhu**  - [zhukaihan](https://github.com/zhukaihan)

## License

This project is licensed under the Creative Commons License - see the [LICENSE.md](LICENSE.md) file for details
