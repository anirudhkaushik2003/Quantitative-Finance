### Option
 - The right but not compulsion to buy or sell a stock/item at a fixed price

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
