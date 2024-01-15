# Backtester MT4 ReadMe

## Description
This ReadMe file provides an overview of the code for the Backtester MT4 developed by Forex Robot Easy Team. This code is designed to streamline and automate the backtesting process for forex trading strategies. Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit the official website: [Forex Robot Easy Backtester MT4 Review](https://forexroboteasy.com/forex-robot-review/backtester-mt4-review-streamline-your-forex-strategy/)

## Variables
- `stopLoss`: Specifies the stop loss level for a position.
- `takeProfit`: Specifies the take profit level for a position.
- `lotSize`: Specifies the lot size for a position.
- `autoStopLoss`: Indicates whether the stop loss level should be set automatically.
- `autoTakeProfit`: Indicates whether the take profit level should be set automatically.

## Functions
1. `openPosition(double price, int type)`: Opens a position at the specified price and type.
2. `closePosition(double price, int type)`: Closes a position at the specified price and type.
3. `setStopLossTakeProfit(double price, int type)`: Sets the stop loss and take profit levels at the specified price and type.
4. `calculatePLPoints(double entryPrice, double exitPrice, int type)`: Calculates the profit/loss points based on the entry and exit prices and type.
5. `calculateLots(double riskPercentage, double accountBalance)`: Calculates the lots based on the risk percentage and account balance.
6. `exportToCSV(double plPoints, double lots, double orderPLResult, double balance)`: Exports the data to a CSV file in a structured format.
7. `OnStart()`: The main function to execute the backtesting algorithm.

## How it Works
1. The user inputs the desired stop loss, take profit, lot size, and auto settings.
2. A buy position is opened at a specified price (1.2345) and type (OP_BUY).
3. The stop loss and take profit levels are set based on the user's input. If auto settings are enabled, the levels are set automatically.
4. The buy position is closed at a specified price (1.2456) and type (OP_BUY).
5. The profit/loss points are calculated based on the entry and exit prices and type.
6. The lots are calculated based on the risk percentage and account balance.
7. The data, including profit/loss points, lots, order PL result, and balance, is exported to a CSV file in a structured format.

## Product Description
The Backtester MT4 by Forex Robot Easy Team is a powerful tool designed to streamline the backtesting process for forex trading strategies. With this code, traders can easily define their stop loss, take profit, lot size, and auto settings, and execute the backtesting algorithm with just a few lines of code.

This code provides functions to open and close positions, set stop loss and take profit levels, calculate profit/loss points and lots, and export data to a CSV file. By automating these tasks, traders can save time and effort in analyzing the performance of their strategies.

Please note that this code is provided as a sample and ForexRobotEasy is not the official developer of this product. To find the official developer and access the complete functionality of the Backtester MT4, please visit the official website mentioned above.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy Backtester MT4 Review](https://forexroboteasy.com/forex-robot-review/backtester-mt4-review-streamline-your-forex-strategy/).
