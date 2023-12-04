# GARCH-Model-Intraday-Algorithmic-Trading-Strategy

</br>
<div align="center">
<a href="https://www.python.org/"><img src="./readme-content/Python.png" width="75" height="75"></a>
<a href="https://jupyter.org/"><img src="./readme-content/Jupyter.png" width="70" height="75"></a>
<a href="https://numpy.org/"><img src="./readme-content/Numpy.png" width="75" height="75"></a>
<a href="https://matplotlib.org/"><img src="./readme-content/Matplotlib.png" width="75" height="75"></a>
<a href="https://pandas.pydata.org/"><img src="./readme-content/Pandas.png" width="75" height="75"></a>
</div>

</br>

## Overview

- This repository is the result of following [this tutorial](https://www.youtube.com/watch?v=9Y3yaoi9rUQ) from Freecodecamp regarding how machine learning can be applied to algorithmic trading
- The purpose of following this tutorial was to expand my machine learning skills into an area of which I have nascent knowledge but an interest in, which is algorithmic trading
- The content of this repository involves applied daily and 5-minute intraday trading data to fit a GARCH model, in order to calculate volatility, prediction premium, and ultimately generate a position and final strategy returns

## Algorithmic Trading Strategy Overview

- The process begins by loading both simulated daily and simulated 5-minute data for analysis.
- Following this, a function is defined to fit a GARCH model, allowing for the prediction of 1-day ahead volatility within a rolling window.
- Subsequently, the prediction premium is calculated, and a daily signal is formed based on this information.
- This daily signal is then merged with intraday data, where additional intraday indicators are calculated to form the overall intraday signal.
- Utilizing the generated signals, positions are entered, and these positions are held until the end of the day as per the strategy.
- Finally, the strategy returns are calculated, providing a comprehensive assessment of the performance of the strategy based on the implemented GARCH model and intraday signals.

View the actual.ipynb file to see the code implementation of the strategy
