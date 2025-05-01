# stock-trading-algorithm
## Trading algorithm/bot - Project is a work in progress (WIP)

### Current Features

The user enters a stock symbol and the amount they want invested.

The bot scrapes twitter and reddit posts related to the stock and analyzes the sentiment.

Then it analyzes the price history of the stock using several formulas to check if its in uptrend.

If both conditions are true, the bot places a trade.

### WIP Features
Improve automation by:

- Having the bot sell if proft/loss crosses a certain threshold.

- Adding a list of popular stock symbols for the bot to cycle through until it finds one that meets our conditions.

- In order to have the two features above, we want to have the bot loop through each condition until it is met. When the main
  function is ran, the bot will search for a good stock. When found it will place a buy order. Then the second loop starts 
  where every minute the bot will check the price for a proft/loss. If it passes our thresholds, it will sell.
