# Market_regime_classification_for_swing_trading
Market regime classification for swing_trading

This is my capstone project in partial fulfillment for the award of MSc Financial Engineering from World Quant University. 
The project understudied the use of Hidden Markov model to classify the regime states of several assets. 
With the regime states information ascertained beforehand, selected trading strategies were backtested with the selected assets to obtain 
which of the assets performed well with any of the moving average and crossover strategies in terms of annual and cumulative returns 
and riskadjusted return performance. The algorithm used for market regime classification and backtesting of the strategies were developed in python programming language

You may email me at mkhamisnabil@gmail.com for a detailed report on the project, but below is a section of the report.

Section 1: Introduction
Volatility has been an inevitable factor in the US equities, thus a great need to capitalize on 
medium-term and short-term goals based on past descriptive models of the market, which can 
assist in evaluating underlying values as well as predictive future modelling. Ten(10) Major 
equities we intend to investigate and classify are Nvidia NVD, Advanced Micro Devices AMD, 
Apple AAPL, S&P500 ^GSPC, Tesla TL, Microsoft MSFT, Facebook FB, American Airline 
AAL, Uber Technologies UBER and Intel INTC.
Understanding the underlying value and performance of any equity requires the metric of 
volatility effects within a market regime. The US equity market has been one that has been 
affected gravely by that metric of volatility. 
We are therefore proposing to investigate swing trading on popular US equities using certain 
indicators to evaluate their performances. To do this we are going to investigate markets 
classification of equities, and potentially the application of swing trading using options to 
increase leverage. On top of these methods, we are also going to try to apply regime shifts in our 
model. In regards to regime shifts, there are a few articles that are pertinent, and can be 
combined in their approaches to perhaps give a better accuracy for a swing trading strategy. 