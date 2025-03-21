# Purple_block
Best Trade Finder

This Python script helps find the best **buy** and **sell** prices in a list of stock prices to maximize profit.

## How It Works
1. The function finds the lowest price to **buy**.
2. Then, it finds the highest price **after** the buy price to **sell**.

## Usage

### Example:
```python
from trade import best_trade

prices = [5, 2, 1, 6, 9, 7]
buy, sell = trade(prices)
print(f"Best Buy Price: {buy}, Best Sell Price: {sell}")
```

### Output:
```
Best Buy Price: 1, Best Sell Price: 9
```

