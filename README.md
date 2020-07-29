# Quant-Trading

## Introduction 
The following project is an ongoing developmental work for deep learning based algorithmic trading bot. The goal is to backtest stratergies after every trading session and tune learning parameters in order to maximize profit. The first approach to algorothmic trading is done using the implementation of technical indicators in trading

### MACD Indicator Stratergy 
The MACD Indicator is a popular indicator in the field of technical trading. Buying and Selling signals are generated based on exponential moving average crossovers — ie. the signal line and the MACD line crossover. In the implementation, <b>AAPL</b> has been backtested on this stratergy

#### Algorithm - 

• Sell at an anticipation of a bearish momentum: When MACD Line in the higher time frame crosses the signal line from above at an intersection > $0. </br>
• Buy at an anticipation of a bullish momentum: When MACD Line in the higher time frame crosses the signal line from below at an intersection < $0. </br>

#### Results - 
• <i>Initial investment</i> - $18.86 AAPL Stock </br>
• <i>Trading Time</i> - June 03, 2009 - June 03, 2019 </br>
• <i>Profit</i> - $90 </br>
• <i>Position</i> - 1 share AAPL </br>
• <i>Number of trades</i> - 25 </br>
• <i>Number of non-profitable trades</i> - 7 (28%) </br>
• <i>Number of profitable trades</i> - 18 (72%) </br>

![Visualization of profits and losses](Images/bubble.png)

