# Crypto-AI

The project aims to create ML based trading models.

Currently, Okex API has been explored through 3 main aspects:
- Account informations, positions, transactions/bills
- Trading (SPOT / Futures with TP/SL)
- Market data (can't specify dates, not used actually)

Market data is being extracted from BINANCE API:
- Historical data (1m, 15m, 30m, .....)
- Streaming by seconds using SQLLite

Binance API documentation: https://python-binance.readthedocs.io/en/latest/market_data.html#id10

Okex API documentation: https://www.okx.com/docs-v5/en/

Next, exploratory analysis and testing different forecast & classification models would be studied following the scientific reasearch available in articles_ressources/ folder.


