---
author: chappjc
published_utc: 2019-08-05
---

### Development Domains

- DEX server (daemon only, no web interface)
- DEX client (for user mgmt, placing orders, pulling/displaying market data, communication between DEX server and two or more assets' wallets, control of the wallets, monitoring for transactions on multiple chains ideally via wallet passthrough but perhaps direct chain server connection) -- note that assets should be configurable in some general way such as RPC config and function-to-RPC spec.
  * command line UI (min viable)
  * simple web-based UI?
  * electron-based GUI like Decrediton (future)
- wallet modifications
  * for dcrwallet, ...
  * for btcwallet (assuming we're using this BTC wallet), ... 

### Server Components

- client messaging and communication hub (i.e. JSON-RPC websocket client messaging, communication and signaling to other dex components depending on the message)
- dex manager (Knows and controls markets, routing market-related messages/operations to relevant market manager, user-related messages to user manager, etc. Coordinates DEX operation like startup/suspension/shutdown/admin)
- user manager (coordinate registration, fee payment, orders, trades, and settings)
- market managers (One for each market. Validates incoming orders. Builds epoch queues, and employs: a book manager, order matcher, swap executor, etc. to run the market.)
- book managers (for a market, keep the book, inserting and removing orders, providing book stats like depth tables for charting)
- order matcher (operates on epoch queue and order book to make matches for swap)
- swap executor (from match to completed swap)
- historian (storage and retrieval of trade, order, stats, etc. history)
- DEX DB backend (persistent data for all these components, ideally only known directly by dex manager)
- asset backend (implement txn monitoring for swaps, fee payment, etc.) - plugin capable?
- dex wallet (the DEX wallet(s) for fees. may be backend to a wallet process, or just xpub key(s) plus assent backend interface) - plugin capable?
- http API (status, chart data, etc.)
