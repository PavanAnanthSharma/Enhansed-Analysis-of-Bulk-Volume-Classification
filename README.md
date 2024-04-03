## Bulk Volume Classification - REVAMPED

### Background

#### The Goal:
Identify information-based trading activity.

**What does that mean?**

Informed traders profit by buying on good news and selling on bad news.

#### Motivation: Why we Care?

Trade data signals underlying private information, crucial for market understanding.

#### Traditional Approaches:

Historical algorithms, like Lee and Ready (LR), struggle in high-frequency markets due to order complexities and market fragmentation.

### Problem:

Identifying individual trade aggressors is challenging amid complex market dynamics.

### Solution:

Bulk Volume Classification (BVC) algorithm aggregates trades by volume or ticks, providing a better indicator of informed-based trading.

### Methodology:

Regression analysis reveals a positive correlation between absolute order imbalance and spread in a given bar.

### Our AIM:

Implement BVC using ThetaData historical data, enhancing market understanding and informing future trading bot strategies.

**References:**

1. [Easley, D., López de Prado, M. M., O’Hara, M., 2016. Discerning Information from Trade Data. Journal of Financial Economics 120,2 269-285.](https://www.sciencedirect.com/science/article/abs/pii/S0304405X16000246)

2. [Panayides, Marios A. and Shohfi, Thomas and Smith, Jared D., Bulk Volume Classification and Information Detection (April 14, 2019). Journal of Banking & Finance, Vol. 103, pp. 113-129, 2019](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2503628)
