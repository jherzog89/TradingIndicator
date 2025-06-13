This strategy has been created for illustration purposes only and should not be relied upon as a basis for buying, selling, or holding any asset or security.
Jason's minimalistic buy/sell indicator: 
1) We want to cut out volatility noise of a green bar in a downtrend and a red bar in an uptrend:
    if the bar closes above the EMA color it green
    if the bar closes below the EMA color it red 

2) We want a early exit signals ('caution') if we are in a trade and the trend may reverse:
  if in an uptrend and stochastic rsi crosses while above 80 signal a caution potential reversal
  if in a downtrend and stochastic rsi crosses while below the 20 signal a caution potential reversal

3) We want buy and sell signals at beginning of new trends
 if bar closes above EMA and stochastic RSI has crossed below the 20: BUY
 if bar closes below EMA and stochastic RSI has crossed above the 80: SELL
