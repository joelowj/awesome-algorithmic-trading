# awesome-algorithmic-trading

###### An algorithmic trading project typically starts with a trading idea or hypothesis which needs to be (back-)tested based on historical financial data.

1. beta trading - earning market risk premium by investing in exchange traded funds (ETFs) that replicate the performance of index such as S&P500.

2. alpha generation

 * strategies that try to generate positive returns (above a benchmark) independent of the market's performance itself.

 * e.g. if the S&P 500 returns 15% in 2015 and an algorithmic strategy returns 18%, then alpha is +3% points. If the strategy returns 10%, then alpha is -5% points.

 * Simple Moving Averages (SMA) - generate trading signals and market positionings. The basic idea is that a shorter-term SMA being higher in value than a longer term SMA signals a long market position and the opposite scenario signals a neutrla or short market position.

 * Momentum assumes that a financial instrument is expected to perform in accordance with its recent performance for some additional time.

 * Mean-reversion strategies, a financial instrument is assumed to revert to some mean or trend level if it is currently far enough away from such a level.

3. static hedging - hedging against market risks by buying, for example, out of money put options on the S&P 500.

4. dynamic hedging - hedging against market risks affecting options on the S&P 500 by, for example, dynamically trading futures on the S&P 500 and appropriate cash, money market, or rate instruments.

5. asset-liability management - trading S&P 500 stocks and ETFs to be able to cover liabilities resulting from, for example, writing life insurance policies.

6. market making - providing, for example, liquidity to options on the S&P 500 by buying and selling options at different bid and ask prices.
