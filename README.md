# EMECS_tradingbot
Economic Modeling of Energy and Climate Systems (EMECS) Project


In this project, you need to program a bot that automatically trades stocks for you. The bot
should use sophisticated machine learning algorithms to predict future stock prices and then
decide to buy or sell the stock. You should test the performance of the bot empirically over a
certain time frame and for different stocks.

# Data
You can collect your own stock price data for which you want to train the algorithms.
The example data set are daily stock prices of Apple from January to the end of March 2021.
You can use the same set and/or another of your choosing.

# Tasks
* Choose a stock/index/currency/commodity/etc. and collect price data for a certain time
frame that you want to use to train and test the algorithms. To train these algorithms
you should have a sufficient amount of data points. Daily returns are easily accessible
but you can also try to look at intra-day data and go the high-frequency trading route.
* As a benchmark, come up with some easy rules to buy and sell the stock (i.e. buy the
stock if it was down the day before, ...). Also implement an algorithm that buys the stock
at random. Test the performance of the strategies empirically.
* Now use more sophisticated approaches to predict the future stock price and let the
trading bot invest based on these forecasts. This is a typical time series application. Check
if the assumptions of the models hold. Find the best time series model and implement it
into the trading bot. Show the performance.
* Try to use other machine learning algorithms to predict stock prices and compare their
performance.
* Your trading bot should work well for your stock and time frame now. What about
another time frame? Or another stock/index?
* It probably won’t perform as well as it did before and you would need to adjust the
algorithm’s parameters or change it altogether. It requires a lot of time to do that
manually every time. Write a program that automatically finds the best approach for
any given asset and time frame to optimize your trading bot.

# Possible Extensions:
* Assume that your trading bot can also sell short instead of just buying assets.
* In a real setting, you would also need to consider trading fees and probably also taxes.
What would change? How can you take this into account when optimizing your bot?

