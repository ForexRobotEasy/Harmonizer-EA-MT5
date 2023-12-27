# Harmonizer EA MT5

This is the code for the Harmonizer EA MT5 developed by the Forex Robot Easy Team. This expert advisor is designed to place pending orders at calculated grid levels and adjust positions based on market changes. It also includes risk management features and provides trading information through print statements.

## Global Variables

- `LotSize`: Default lot size for each position.
- `GridDistance`: Distance between grid levels.
- `TakeProfit`: Take profit level for each position.
- `StopLoss`: Stop loss level for each position.
- `MaxPositions`: Maximum number of open positions.

## Expert Initialization Function

The `OnInit` function is called when the expert advisor is initialized. It sets initial parameters and account information. In this case, it simply prints a message indicating that the EA has been initialized.

## Expert Deinitialization Function

The `OnDeinit` function is called when the expert advisor is deinitialized. It performs any necessary cleanup operations. In this case, it prints a message indicating that the EA has been deinitialized.

## Expert Start Function

The `OnTick` function is called on each tick of the market. It checks for available positions and calculates entry positions based on the current price and grid levels. If there are available positions, it places pending orders at the calculated grid levels. It also includes sections for adjusting positions based on market changes, checking for news filter, performing necessary trades and risk management, and printing trading information.

## Product Description

The Harmonizer EA MT5 is an advanced forex tool developed by the Forex Robot Easy Team. It is designed to automate the trading process by placing pending orders at calculated grid levels and adjusting positions based on market changes. With its risk management features, it helps traders manage their positions effectively.

Key Features:
- Calculates entry positions based on grid levels and current market price.
- Places pending orders with customizable lot size, take profit, and stop loss levels.
- Adjusts positions based on market changes.
- Includes risk management features to protect trading capital.
- Provides trading information through print statements.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5. For detailed reviews and trading results of this product, you can visit [here](https://forexroboteasy.com/forex-robot-review/harmonizer-ea-mt5-review-advanced-forex-tool-with-low-drawdown/).
