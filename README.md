# algo_trading
## Simple Trend following Strategy
I am testing a very simple trend following strategy based on several technical indicators such as moving average and bollinger band.
The research is to find different in/out protocal's influence on Sharpe Ratio / MDD


how to use RSI:
short_term = 6
long_term = 12

涨幅越接近跌幅，RSI越接近50.
涨幅>跌幅， RSI >50
MAX(RSI) = 100---NO LOSS
MIN(RSI) = 0 ----NO GAIN

RSI>70 OVERBUY
RSI<30 OVERSELL
