# MyTradingScripts

## Non-Repainting Indicator. Intra-Bar Percentage Trail

### Description
This Pine Script strategy sets up an intra-bar percentage trailing stop for long and short positions. It dynamically calculates trailing stop prices based on the highest and lowest prices encountered during trades and ensures that these stops do not repaint, providing reliable backtesting results.
Purpose: This script sets up a strategy with trailing stops that adjust based on the highest and lowest prices reached.
Non-Repainting: By ensuring signals are based on past and present data only, we avoid repainting, providing more reliable backtest results.
### Usage
- **Trailing Stop Percentage**: Adjustable percentage for trailing stops (default is 2%).
- **Entry Conditions**: Enters long/short positions based on the 20-period simple moving average.
![image_2024-12-19_17-53-42](https://github.com/user-attachments/assets/4cad8e49-e577-4681-aa7f-a9941bf95892)

### Example
```pinescript
//@version=5
strategy("Intra-Bar Percentage Trail", overlay=true, default_qty_type=strategy.percent_of_equity, default_qty_value=10)
// Script content...

  ### This README file will help others understand your project and how to use your scripts. If you have any more questions or need further assistance, feel free to ask!

