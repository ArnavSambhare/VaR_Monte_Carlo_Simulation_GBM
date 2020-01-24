# VaR_Monte_Carlo_Simulation_GBM

This contains the code to estimate the VaR using the Monte Carlo Simulation.<br>
<br>
The Geometric Brownian Motion is:<br>
<a href="https://www.codecogs.com/eqnedit.php?latex=\Delta&space;S&space;=&space;\mu&space;*&space;S*\Delta&space;t&space;&plus;&space;\sigma*\epsilon*S*\sqrt\Delta&space;t" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\Delta&space;S&space;=&space;\mu&space;*&space;S*\Delta&space;t&space;&plus;&space;\sigma*\epsilon*S*\sqrt\Delta&space;t" title="\Delta S = \mu * S*\Delta t + \sigma*\epsilon*S*\sqrt\Delta t" /></a><br>
where:<br>
<a href="https://www.codecogs.com/eqnedit.php?latex=\epsilon" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\epsilon" title="\epsilon" /></a> is a random number generated from the standard normal distribution.<br>
S = Stock Price<br>
<a href="https://www.codecogs.com/eqnedit.php?latex=\mu" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mu" title="\mu" /></a> = Expected Return<br>
<a href="https://www.codecogs.com/eqnedit.php?latex=\sigma" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sigma" title="\sigma" /></a> = Volatility of the stock
t = Time period
<br>
The ending prices of all these simulation are arrange in the ascending order and the (100-x)th percentile value is calculated.<br>
VaR(x%) = Current Price of the Stock - (100-x)th percentile value
