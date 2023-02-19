# Introduction

## Architecture

## Supported Trading Scenario

### Algorithmic Trading
Algorithmic trading(AT) is a supported trading scenario that involves using deep reinforcement learning methods to execute trades. This scenario is often used by traders who wish to execute large numbers of trades quickly and efficiently(especially High Frequency Trading).

For more information, please refer to [Algorithmic Trading](https://www.investopedia.com/articles/01/022801.asp).

### Order Execution
Order execution(OE) is a supported trading scenario that involves placing orders to buy or sell securities. This scenario is often used by traders who wish to execute trades automatically and optimally. 

The key difference of this OE and algorithmic trading is that OE can only put an action at one side. For example, if the OE task is to buy one share of BTC, you cannot put an "ask" order even if you still have BTC in your hand. In OE, we want to sell at the highest price or buy at the lowest price. Therefore, the optimization target is set to be the amount of money we sell. If the target is buying, our target will be negative. Both targets will be optimized to their maximum value. All of the trades will be conducted at their closing price.

For more information, please refer to [Order Execution](https://www.investopedia.com/articles/01/022801.asp).

### Portfolio Management
Portfolio management(PM) is a trading scenario that involves managing a collection of investments over time. It's used by investors who want to minimize risk and diversify their investments. This scenario often involves a long-term investment strategy, rather than focusing on short-term trading opportunities.

For more information, please refer to [Portfolio Management](https://www.investopedia.com/terms/p/portfoliomanagement.asp).

## Model Zoo



