# Cryptocurrency CLI

Cryptocurrency CLI lets you monitor cryptocurrencies in your portfolio and track your earnings through the command line.  It uses the coinmarketcap.com API to fetch crypto data.

![Cryptocurrency CLI](https://i.imgur.com/t51gp74.png)

## Features

### General
1. Command Line Interface
1. Supports all coins on CoinMarketCap
1. Track your portfolio holdings
1. Currency Support

### Bar Graph
1. Percentage breakdown of holdings
2. Colored Horizontal Bars
3. Portfolio value

### Crypto Table
1. Coin Rank
1. Price
1. Coins Owned
1. Net Worth
1. 24 Hour Volume
1. Market Cap
1. % Change 1 Hour
1. % Change 1 Day
1. % Change 1 Week
1. Last Updated

## Installation Instructions


1. Git Clone the repo

    ```
    git clone https://github.com/TUDTech/Cryptocurrency_CLI
    ```

1. Enter the repository

    ```
    cd Cryptocurrency-CLI && npm install
    ```

1. Run

    ```
    npm start
    ```

1. Edit portfolio.json

    ```json
    {
      "bitcoin": ".002",
      "bitcoin-cash": ".002",
      "chainlink": "666",
      "dash": ".002",
      "dogecoin": "10000",
      "ethereum": ".0688",
      "litecoin": ".1",
      "monero": ".0036",
      "siacoin": "1200",
      "steem": "2"
    }
    ```

## Command Line Options

Currency: You can use `-c` or `--currency` to look up crypto data in another currency.  The default currency is USD and the API supports AUD, BRL, CAD, CHF, CLP, CNY, CZK, DKK, EUR, GBP, HKD, HUF, IDR, ILS, INR, JPY, KRW, MXN, MYR, NOK, NZD, PHP, PKR, PLN, RUB, SEK, SGD, THB, TRY, TWD, ZAR.

  ```
  npm start -- -c eur
  npm start -- -c aud
  ```

## Contributing

Thanks all for your contributions...
    
![Screen Shot 2021-03-21 at 19 11 59](https://user-images.githubusercontent.com/81108192/111917690-519f4380-8a79-11eb-9d01-de457b1655f6.png)
    
ETH WALLET: 0xA1134858c168568CBE37649D16723eC8F782e0A2

![Screen Shot 2021-03-21 at 21 56 54](https://user-images.githubusercontent.com/81108192/111922186-5b807100-8a90-11eb-8504-a3fc3ae35052.png)

BTC WALLET: 3N928MmFq51kbf6fE3fxJbtggBhcjMAhSQ
