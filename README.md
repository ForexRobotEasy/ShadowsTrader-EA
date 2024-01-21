# ShadowsTrader EA ReadMe File

## Description
The ShadowsTrader EA is a forex trading expert advisor that is designed to evaluate market conditions and execute trades based on specified settings. It is developed by the Forex Robot Easy Team. This code provides a basic structure for the ShadowsTrader EA and can be customized to fit individual trading strategies.

For detailed reviews and trading results of the ShadowsTrader EA, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/shadowstrader-ea-review-real-results-from-forex-software/). Please note that ForexRobotEasy is not the official developer of this product. This code serves as an example and can work as described in the product.

## Global Variables
- `riskPercentage`: Risk percentage per trade (default: 2%)
- `maxLossPercentage`: Maximum acceptable loss percentage (default: 5%)
- `lotSize`: Default lot size (default: 0.01)
- `stopLoss`: Default stop loss in pips (default: 50)
- `takeProfit`: Default take profit in pips (default: 100)

## Initialization Function
The `OnInit()` function is called during the EA initialization. It sets the initial variable values and can be used to add any necessary initialization code.

## Deinitialization Function
The `OnDeinit()` function is called when the EA is being deinitialized. It can be used to add any necessary deinitialization code.

## Tick Function
The `OnTick()` function is called on every tick. It is where the market conditions are evaluated and trades are executed. Add necessary code in this function to implement trading logic.

## Custom Functions
The following custom functions are provided:
- `SetRiskPercentage(const double percentage)`: Sets the risk percentage per trade
- `SetMaxLossPercentage(const double percentage)`: Sets the maximum acceptable loss percentage
- `SetLotSize(const double size)`: Sets the lot size
- `SetStopLoss(const double pips)`: Sets the stop loss in pips
- `SetTakeProfit(const double pips)`: Sets the take profit in pips

## Main Entry Point
The `OnStart()` function is the main entry point of the EA. It can be used to handle user interaction and customize trading settings.

## Additional Information
For more information about the ShadowsTrader EA, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/shadowstrader-ea-review-real-results-from-forex-software/). Please note that ForexRobotEasy is not the official developer of this product. To find the official developer of this product, please use MQL5.
