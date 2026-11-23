<h1> Algorithmic Trading Project</h1>

<h2> Introduction </h2>
This project aims to show basic yet effective time series techniques. It uses Moving Averages to determine when you would create buy and sell signals within a trading strategy. These techniques are called Crossover Strategies or Trend Following Strategies and are beginner strategies used by trading specialists. This project explores 3 different approaches. A Simple Moving Average (SMA) strategy, an Exponentially Moving Average Strategy (EMA) and a Trend Following Strategy using Bollinger Bands - Bollinger Bands are a technical analysis tool used in finance to protect traders against large volatility spikes by setting upper and lower 'bands' to initiate buy and sell signals before the price levels move beyond the 'bands'.

<H2> Objective </H2>
The objective of this project was to find which of the 3 strategies used would best capture the trend. It also allows stakeholders to determine which strategy would yield the best returns and the have least risk. The choice of the strategy would be up to the individual.

<h2> Data and Packages </h2>
<b> Packages: </b> yfinance, numpy, pandas, plotly, statsmodels  <br>
<b> Data Source: </b> obtained from yfinance library

<h2> Data Cleaning and EDA </h2>
The yfinance library uses real data which has already been cleaned and structured, therefore we did not need to clean the data nor perform exploratory data analysis. We only used the Close Price column from the data.

<h2> Conclusion </h2>
At the end of this project we can see that each strategy has its pros and cons. The SMA Strategy we can see has less risk/volatility compared to a simple buy-and-hold strategy but the buy-and-hold strategy does have higher returns. The EMA Strategy had similar risk/volatility to the SMA Strategy but had higher returns compared to both the buy-and-hold strategy and the SMA Strategy. The EMA Strategy reacts faster to the market compared to the SMA Strategy and may not seem significantly better, however, in finance small changes equate to large returns and losses. The final strategy is the Trend Following Strategy using Bollinger Bands. The Bollinger Bands Strategy has the least risk/volatility compared to the other previously discussed strategies and as expected the returns are much lower compared to the other moving average strategies and the buy-and-hold strategy. The Bollinger Bands Strategy is clearly the safest approach and the EMA Strategy is the best in terms of returns. It would be up to the individual to choose which approach is suited to there needs. The data used updates every time the notebook is run and so values may change constantly.
