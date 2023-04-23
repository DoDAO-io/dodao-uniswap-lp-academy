## Uniswap V3 Ticks and Price Ranges


## Ticks in Uniswap V3

Uniswap V3's innovation starts with ticks. Ticks divide the price range into numerous granular intervals, making trading on V3 similar to order book exchanges.

    


---
## Advantages of Tick Design

The tick design enables Uniswap V3 to possess the merits of both AMM and order book exchanges. Ticks have a predefined price range, with trades following the AMM pricing function.

    


---
## Price Range Calculation

The price range of each tick is decided with a 0.01% (1 basis point) price change between adjacent ticks, based on a multiplication factor of 1.0001.

    


---
## Price Range Coverage

Uniswap V3's int24 tick state variable allows for a wide range of prices, covering >99.99% of all asset prices in the universe.

    


---
## Tick Index Calculation

To find the tick index for a specific price, simply take the logarithm base 1.0001 of the price. This helps map the price to its respective tick.

    
   