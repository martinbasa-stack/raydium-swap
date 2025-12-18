# raydium-swap
Python RaydiumSwap class for building transactions on solana

The class only builds a transaction for you, then you need to signe it and send it to solana network.

data sources:
* [trade API](https://docs.raydium.io/raydium/traders/trade-api)
* [https://docs.raydium.io/raydium/traders/trade-api](https://api-v3-devnet.raydium.io/docs/)

# Class functions
All the functions have DOC
* ``generate_transaction()`` Creates a transaction
* ``get_price()`` Calculates a price in smallest units if one token has 6 decimals and the other 9 you need to multiply or divide buy 1000
* ``get_rpcs()`` Returns a list of rpcs 
* ``get_pools_info()`` Returns full info of pools the transaction will use
* ``get_routes()`` Returns routes the transaction will use



