# MQL5 EA Idea Pro mt5

## Description
This is a simple example of a MQL5 Robot. It is an automated trading system that places a Buy order when there are no open orders. The trading operation can be enabled or disabled. 

## How to Use

1. Input your preferred trading lot size, Stop Loss in points, Take Profit in points, and Magic Number.
2. 2. Run the script to start the trading robot.
   3. 3. The robot will place a Buy order when there are no open orders.
      4. 4. The OnTrade event handler checks if the last operation was successful and prints a corresponding message.
         5. 5. Trading can be enabled or disabled using the EnableTrading() and DisableTrading() functions respectively.
           
            6. ## Input Parameters
            7. - `Lots`: Trading lot size
               - - `StopLoss`: Stop Loss in points
                 - - `TakeProfit`: Take Profit in points
                   - - `MagicNumber`: Magic Number
                    
                     - ## Global Variables
                     - - `ticket`: Order ticket
                       - - `isTradingEnabled`: Trading switch
                        
                         - ## Functions
                         - - `OnTick()`: Event handler that performs trading operations when trading is enabled.
                           - - `OnTrade()`: Event handler that checks if the last operation was successful.
                             - - `DisableTrading()`: Function to disable trading.
                               - - `EnableTrading()`: Function to enable trading.
                                
                                 - ## More Information
                                 - For more information, please visit the development site: [Idea Pro MT5](https://forexroboteasy.com/forex-robot-review/review-ea-idea-pro-mt5-a-convenient-forex-software-by-vasily-strukov/)
