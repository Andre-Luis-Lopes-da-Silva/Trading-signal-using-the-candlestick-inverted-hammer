# Trading-signal-using-the-candlestick-inverted-hammer
Brief study analyzing the potential of using the inverted hammer candlestick in trending of assets using python language. 

Candlestick charts are used by traders to determine possible price action based on past patterns. Candlesticks originated from Japanese rice merchants and traders to track market prices and daily momentum hundreds of years before becoming popularized in the United States. There are much candlestick patterns. One of them is the inverted hammer. Inverted Hammer is a bullish candlesticks chart formation at the bottom of downtrends. However, this same form found at the top of uptrends is called shooting star. The shooting star is a type of candlestick pattern and refers to the candle's shape and appearance, representing a potential reversal in an uptrend.

![Inverted-hammer-and-shooting-star](https://user-images.githubusercontent.com/78765404/209818099-ee2ed998-3f78-4d60-8a44-624374ac53f1.png)
Figure 1. Differences of an inverted hammer and a shooting star, the figure is the same, but where it appears is what differ it.  

Historical data of assets can be used to performe backtesting. Backtesting means the process of testing a trading strategy on historical data to assess its accuracy. Moreover, it can be used to genereate trading signals to indicate buy or sell of assets. 

In this study, this candlestick indicates four signals, two for buy and two for sell. 

![inverted_hammer](https://user-images.githubusercontent.com/78765404/209820303-87fe3731-03af-4911-bfa7-502e24590863.png)

Figure 2. Candlestick chart created using Plotly demonstrating the positions of the inverted hammer.

The buy signal is confirmed when the close of the next candle is larger than the close of the inverted hammer and the sell signal is confirmed when the close of the next candle is smaller than the close of the inverted hammer. 
