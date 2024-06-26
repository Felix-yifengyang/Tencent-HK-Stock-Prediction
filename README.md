### I use the historical price information between 2015 and 2020 to train and validate my machine learning model, and tune the parameters in the trading model based on the prediction. 
### I test the real business performances of the four investor types based on the price movements of Tencent in 2021. 
### I apply directly the fine-tuned machine learning model and trading mechanisms DIRECTLY WITHOUT CHANGE to the price movements of Tencent in 2021. 
### The trading bot should buy or sell 100 shares of Tencent’s stock for each trading operation.
The “sell” signal is controlled by a predefined mechanism with three parameters (g, l, and d): the trading bot holds the stock until it reaches a certain percentage gain (g), a certain percentage loss (l) or a sells after a certain amount of days (d). If you choose to, you can add the “sell” signal generated by your machine
   
learning model as an additional sell condition. This is optional though. The final trading mechanism thus has three parameters (g, l, d) and the goal is to maximize profit.
You are required to create four investor types by changing these parameters. The “Short-term Investor”, “Medium-term Investor”, “Long-term Holder” and “The Random Investor”.
 The Short-term Investor — This type of investor buys and holds the stock for a very short period of time. The investor also looks for small gains. This investor is also scared of losses, so the investor tends to sell the stock for a loss if the stock drops even a little bit. For short-term investor, the holding period d should not exceed 5. The other two parameters, g and l, are free to set.
 The Medium-term Investor — This type of investor buys and holds the stock for a moderate period of time. The investor also looks for higher gains and has a higher tolerance for losses compared to the Short-term Investor. The holding time d should be between 10 to 15 days. The other two parameters, g and l, are free to set.
 The Long-term Investor — This type of investor tends to hold the stock longer. The holding time d should exceed or equal to 20 days. The other two parameters, g and l, are free to set.
 The Random Investor — This is the type of investors that are new to the stock market. They tend to trade stocks irrationally. So they do not use any strategy to trade stocks. They randomly buy stocks and randomly sell them whenever they feel like it.
