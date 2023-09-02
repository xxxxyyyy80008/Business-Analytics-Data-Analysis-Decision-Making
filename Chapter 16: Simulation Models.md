# Business Analytics: Data Analysis & Decision Making - 6th Edition *by S. Christian Albright, Wayne L. Winston*

**Sep 2023**

## Chapter 16: Simulation Models

### 16-2a Bidding for Contracts

[Download Contract Bidding-@RISK.xlsx](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/Excel%20Models/chapter%2016/Contract%20Bidding-%40RISK.xlsx)

In situations where a company must bid against competitors, simulation can often be used to determine the company’s optimal bid. Usually the company does not know what its competitors will bid, but it might have an idea about the range of the bids its competitors will choose. In this section, we show how to use simulation to determine a bid that maximizes the company’s expected profit.

Miller Construction Company must decide whether to make a bid on a construction project. Miller believes it will cost the company $10,000 to complete the project (if it wins the contract), and it will cost $350 to prepare a bid. However, there is uncertainty about each of these. Upon further reflection, Miller assesses that the cost to complete the project has a triangular distribution with minimum, most likely, and maximum values $9000, $10,000, and $15,000. Similarly, Miller assesses that the cost to prepare a bid has a triangular distribution with parameters $300, $350, and $500. (Note the skewness in these distributions. Miller recognizes that cost overruns are much more likely than cost underruns.) Four potential competitors are going to bid against Miller. The lowest bid wins the contract, and the winner is then given the winning bid amount to complete the project. Based on past history, Miller believes that each potential competitor will bid, independently of the others, with probability 0.5. Miller also believes that each competitor’s bid will be a multiple of its (Miller’s) most likely cost to complete the project, where this multiple has a triangular distribution with minimum, most likely, and maximum values 0.9, 1.3, and 1.8, respectively. If Miller decides to prepare a bid, its bid amount will be a multiple of $500 in the range $10,500 to $15,000. The company wants to use simulation to determine which strategy to use to maximize its expected profit.

#### Objective: To simulate the profit to Miller from any particular bid, and to see which bid amount is best.

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_1.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_2.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_3.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_4.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_5.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_6.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_7.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_8.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_9.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_10.png)

![png](https://github.com/xxxxyyyy80008/Business-Analytics-Data-Analysis-Decision-Making/blob/main/img/ch16/cb_11.png)
