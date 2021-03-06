# Trade Strategy App

Learning about trading requires a lot of discipline, especially to avoid repeating the same mistakes. Experienced traders recommend to carry out a trades register to be able to review the trades that were either succesful or unprofitable.

Training as a trader requires good tracking of trades and management of capital risk. Therefore, a website and a mobile app can be a very useful tool for the trader to improve his performance and not ruin his account in a few minutes.

# First Approach

## Trades & Balance Screens

![alt tag](https://i.imgur.com/nWO9TTm.png)

## Trade Detail & Trade Notes Screens

![alt tag](https://i.imgur.com/raa3HSa.png)

## Use Cases v1

* **Trades**
  * Create User Account
  * Configure Initial Capital with exchange
  * Create trade
  * Show trade detail in realtime
  * Add note to trade
  * Close trade

* **Balance**
  * Calculate balance filter by time frames
  * Show numbers of positive and negative closed trades in a period of time
  * Show list of closed trades related to one or several exchange

* **Risk Capital**
  * Allow the user to calculate how much money he should put in risk 
  * Show how much money is compromised

## Use Cases v2
  * Connect app with exchange
  * Create trade in exchange using trade setup from Trade Stratefy App
  * Active alerts to inform about the changes price of one coin
  * Retrieve state orders (filled, partially filled, canceled) - Realtime
  * Fetch Price Tickers (contains statistics for a particular market/symbol for some period of time in recent past, usually last 24 hours)
  * Fetch Trade (Order Filled)


## Arquitecture

![alt tag](https://i.imgur.com/COAX8o4.png)

## Getting Started

Clone the repo:
```sh
git clone https://github.com/igiagante/tradeApi.git
cd tradeApi
```

Install dependencies
```sh
npm install
```

Start server
```sh
# Start server
npm start
```

Tests
```sh
# Run all tests (integration & unit)
npm test

# Run coverage with Istanbul
npm run coverage
```

Lint
```sh
# Lint code with ESLint
npm run eslint
```

##### In order to check the coverage report, the file index.html can be found at the folder coverage.
