# Coinmarketcap Parsing

Python3 scrap all the related information about different cryptocurrencies around the [Coinmarketcap](https://coinmarketcap.com/) 

### Installation
PyPI

```
pip install package_crypto==0.0.9
```

### Usage

```python
from package_crypto import Pars
scrapper = Pars()
```

### Examples

You need just input a name of **_Cryptocurrency_**

Usage examples:

```python

Please enter the name of the Cryptocurrency: Bitcoin
14.51 ETH0.95%

Loading Data

Please wait, we are loading chart data

The live Bitcoin price today is $43,914.46 USD with a 24-hour trading volume of $31,256,129,348 USD. We update our BTC to USD price in real-time. Bitcoin is up 6.17% in the last 24 hours. The current CoinMarketCap ranking is #1, with a live market cap of $826,938,439,749 USD. It has a circulating supply of 18,830,662 BTC coins and a max. supply of 21,000,000 BTC coins.

If you would like to know where to buy Bitcoin, the top exchanges for trading in Bitcoin are currently Binance, Huobi Global, Mandala Exchange, OKEx,  and FTX. You can find others listed on our crypto exchanges page.

Bitcoin is a decentralized cryptocurrency originally described in a 2008 whitepaper by a person, or group of people, using the alias Satoshi Nakamoto. It was 
launched soon after, in January 2009.

...

```

### Test

Run unit tests with:

```
# after installing the project
run test.py
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
