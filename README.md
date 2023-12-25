README

# Trend Reactor MT4

Trend Reactor MT4 is a forex trading expert advisor developed by the Forex Robot Easy Team. It is a reliable solution for trading in the forex market.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/trend-reactor-mt4-review-reliable-forex-trading-solution/). Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Code Description

The Trend Reactor MT4 code includes the necessary libraries and declares global variables for trading and moving averages. The expert advisor is initialized in the `OnInit()` function where trade parameters and moving averages parameters are set.

The `OnTick()` function is responsible for checking trading conditions and opening positions. It retrieves the current moving average value and compares it with the current price. If the price is above the moving average, a buy position is opened. If the price is below the moving average, a sell position is opened. The function also checks if there are no open positions before opening a new position.

The `OnDeinit()` function is triggered when the expert advisor is stopped or removed. It closes all open positions.

## Usage

To use the Trend Reactor MT4 expert advisor, follow these steps:

1. Include the required libraries: Trade.mqh and MovingAverages.mqh.
2. Declare the global variables: `CTrade trade` and `CMovingAverages ma`.
3. Set up trade parameters in the `OnInit()` function: expert magic number, stop loss, take profit, and trading volume.
4. Set up moving averages parameters in the `OnInit()` function: moving average period and shift.
5. Implement the trading conditions and position opening logic in the `OnTick()` function.
6. Close all open positions in the `OnDeinit()` function.

Please refer to the official MQL5 documentation for more information on using this code and customizing it according to your trading strategy.

## Disclaimer

Please note that ForexRobotEasy is not the official developer of the Trend Reactor MT4. We are only providing a sample code that can work as described in the product. To find the official developer of this product, please use MQL5.
