### Option
 - The right but not obligation to buy or sell a stock/item at a fixed price

### Call option
 - The right to buy a stock/item at a fixed price

### Put option
 - The right to sell a stock/item at a fixed price

### Bond
 - A contract signifying that a given sum of money along with interest is owed to the person owning the bond

Note: All of the above are like contracts which can be exchanged

### Stock Price
 - The current value of a stock/item in the market.

### Strike Price
 - A fixed agreed upon price for a stock/item.

### Expiration Period
 - The period of time for which the bond/contract to buy/sell an item at an agreed upon/fixed price holds.

### Portfolio
 - A collection of various investments

### Arbitrage
 - Sure profit in excess of risk-free return
 - violation of put call parity

### Compound interest
$$Amount = Principal\biggl ( 1 + \frac{rate}{n}\biggr )^{nt} $$
 - Here $r$ is interest rate, $n$ is the number of times the interest is compounded in the given time perion and $t$ is the time period.

### Continuously compounded interest
 - to get the continously compounded interest, we simply evaluate the above at the limit $n \rightarrow \infty$
 $$lim_{n \rightarrow \infty }P\biggl(1+\frac{r}{n}\biggr)^{nt}$$
 - Now,
  $$lim_{n \rightarrow \infty }\biggl(1+\frac{r}{n}\biggr)^{n} = e^r $$
- The above evaluates to
 $$P e^{rt}$$
 - Similarly, if the interest is substracted instead, we get
  $$lim_{n \rightarrow \infty }P\biggl(1-\frac{r}{n}\biggr)^{nt}$$
  =  $$Pe^{-rt}$$

### Put-Call Parity
 - It states that Call Price - Put Price = Stock Price - Strike Price
 - When the interest rate on the bond for the strike price is compounded continuously over the Expiration period $T$ starting from the time $t$ when the values were evaluated is given by
 $$C - P = S - Ke^{-r(T-t)}$$

 - $K$ is the strike price, $S$ is the stock price, $C$ is the call option price and $P$ is the put option value.
 - Here, the compound interest has to be paid over the value of the principal stated in the bond, i.e. if the strike price is $100 with an interest rate of 4.5%, then we'll have to pay interest of 4.5% compounded continuously over the principal sum of $100 before we can sell it.
 - After the expiration period, the portfolio will be worthless regardless of the final price of the stock. 


## [Arbitrage](https://www.investopedia.com/terms/a/arbitrage.asp)
 - Simultaneous purchase and sale of an asset in different markets to exploit any tiny differences in their prices
 - Abitrage trades are made in stocks, commodities and currencies
 - Abitrage takes advantage of the inevitable inefficiences in markets
 - By exploiting market inefficiences, however, the act of abitraging brings markets closer to efficiency
 - It can be used whenever any stock, commodity, or currency may be purchased in one market at a given price and simultaneously sold in another market at a higher price. The situation creates an oppurtunity for a risk-free profit for the trader
 - Arbitrage provides a mechanism to ensure that prices do not deviate substantially from fair value for long periods of time. With advancements in technology, it has become extremely difficult to profit from pricing errors in the market. Many traders have computerized trading systems set to monitor fluctuations in similar financial instruments. Any inefficient pricing setups are usually acted upon quickly, and the opportunity is eliminated, often in a matter of seconds.
 - Arbitrage is a condition where you can simultaneously buy and sell the same or similar product or asset at different prices, resulting in a risk-free profit.
 - Economic theory states that arbitrage should not be able to occur because if markets are efficient, there would be no such opportunities to profit. However, in reality, markets can be inefficient and arbitrage can happen. When arbitrageurs identify and then correct such mispricings (by buying them low and selling them high), though, they work to move prices back in line with market efficiency. This means that any arbitrage opportunities that do occur are short-lived.

 ## [Arbitrage Pricing Theory (APT)](https://www.investopedia.com/terms/a/apt.asp)
  - A pricing model that predicts a return using the relationship between an expected return and macroeconomic factors