### Extended SMA Cross Strategy Overview

#### 1. **Focus**
The **Extended SMA Cross Strategy** focuses on detecting trend reversals and momentum shifts in the market by using two Simple Moving Averages (SMAs). The strategy exploits the lagging nature of SMAs to enter and exit trades based on the intersection of short-term and long-term trends, aiming to capture significant price movements.

___

#### Performance Metrics
![alt Extended SMA Cross](assets/bokeh_plot.png "Extended SMA Cross Strategy")

With a **26.44% return** over almost seven days, the report beat the **Buy & Hold return of -0.38%** by a wide margin, demonstrating the strategy's profitability even in a slightly decreasing market.

Strong risk-adjusted returns are shown by the **Sharpe ratio of 1.74**, and a solid profitability indicator, the **profit factor of 2.56**, showing that the strategy makes $2.56 for every dollar lost. Nearly half of the transactions are lucrative, as indicated by the **48.08%** win rate, with the **best trade** returning 9.07%**. 

Although there is considerable downside risk indicated by the **maximum drawdown of 5.09%**, the **Sortino ratio (infinity)** indicates that the approach performs effectively with little downward volatility.

In summary, this SMA approach exhibits significant profitability, robust risk mitigation, and a remarkable capacity to provide returns despite adverse market circumstances.

___

#### 2. **Market Focus**
This strategy is primarily designed for the **cryptocurrency market**, with a specific focus on **Perpetual Asset Type DOGE (Dogecoin, DOGE/USDC)**. Given its flexibility, the strategy can be adapted to other high-volatility and liquid markets where price trends are clearly defined over short periods.

___

#### 3. **Time Horizon**
The strategy is optimized for **short-term trading**, using a **five-minute interval** and a **maximum 14-day trading window**. It is designed to capture market momentum and trend shifts within a short time frame, making it ideal for traders looking to profit from quick market fluctuations.

___

#### 4. **Indicators**
The strategy employs two key indicators:
- **10-Day SMA**: A short-term SMA that reacts more quickly to recent price movements.
- **30-Day SMA**: A longer-term SMA that smooths out price action over a more extended period.
- **Crossover**: Buy and sell signals are generated when the shorter-term 10-day SMA crosses the longer-term 30-day SMA (Golden Cross) and vice versa (Death Cross).

___

#### 5. **Execution**
The strategy executes as follows:
- **Buy Signal**: When the 10-day SMA crosses above the 30-day SMA, signaling an upward trend, the strategy closes any existing positions and initiates a buy order with **99.9% of available capital**.
- **Sell Signal**: When the 10-day SMA crosses below the 30-day SMA, indicating a potential downtrend, the strategy closes any open positions and initiates a sell order.
- **Position Management**: All positions are closed before a new one is opened to avoid conflicting trades.

___

#### 6. **Why It Works**
The **Extended SMA Cross Strategy** is effective due to:
- **Clear Trend Signals**: The crossover of two moving averages provides clear signals for entering and exiting trades, helping traders avoid emotional decision-making.
- **Momentum Capture**: By using both short-term and long-term SMAs, the strategy can capture changes in market momentum, entering trades at the beginning of new trends.
- **Risk Management**: The strategy’s reliance on SMA crossovers prevents it from making trades during periods of low momentum or noise, leading to more stable and potentially profitable trades in trending markets.
- **Simplicity**: The simplicity of using SMAs makes the strategy easy to understand, monitor, and implement, while still being highly effective in volatile and liquid markets like cryptocurrency.

___

This approach ensures that the strategy systematically takes advantage of momentum shifts in the market, maximizing profitability by entering during trends and exiting during reversals.

___

## Setup
* **Open ExtendedSmaCross.ipynb and run all cell.**
