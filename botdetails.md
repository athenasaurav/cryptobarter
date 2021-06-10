#   Binance Credentials
```
BINANCE_API_KEY = 'yourbinanceapikey'

BINANCE_API_SECRET = 'yourbinanceapisecret'

BINANCE_SYMBOL = 'BinancesymbolpairinUPPERCASE'
```

#   Peatio Credentials
```
PEATIO_API_KEY = 'yourpeatioapikey'

PEATIO_API_SECRET = 'yourpeatioapisecret'

PEATIO_SYMBOL = 'PeatiosymbolpairinLOWERCASE'
```

# Refresh Time Setting 1
Deatils:

Refresh time, to create 10 Buy & Sell Orders, check any done orders, 
if yes create a back order on Binance and cancel the rest BUY & Sell orders. Time in Seconds

```
REFRESH_TIME = 1
```
# Refresh Time Setting 2
Details:

Refresh time, to create 1 Buy Order & immedietly create one Sell Order of same Volume and Price to nullify. 
This creates charts for us. Time in Seconds
```
REFRESH_TIME_JOB1 = 10
```

# No of best Price Buy and Sell data to be fetched from Binance
Details:

Number of Bids and Asks data to be fetched from Binance. 
If the number is 10, 10 Best Bids and 10 Sell Bids will be fetched from Biannce
```
NUMBER_OF_ORDER_FETCH_FROM_BINANCE_ORDER_BOOK = 10 
```

# Random Values generator for Volume
Details :

We will select random values between MIN_ORDER_SIZE & MAX_ORDER_SIZE. 
```
MIN_ORDER_SIZE = 0.00005    
MAX_ORDER_SIZE = 0.005      
```

# Rounding up Values of Price 
Details :

Rounding up the Price and Volume after Demical 
```
PRICE_PRECISION = 2         # Rounding the Price upto 2 decimal Places
VOLUME_PRECISION = 5        # Rounding the Volume upto 5 decimal Places
```
# BUY PRICE DIFF from Binance 
Details :

99.5% price of the Biannce BUY Price, For Ex : Price on Binance for BUY is 100, on peotio it will be 99.5
```
BUY_PRICE_DECREASE_PERCET = 0.995   
```

# SELL PRICE DIFF from Binance
Details:

100.5% price of the Biannce SELL Price, For Ex : Price on Binance for SELL is 100, on peotio it will be 100.5
```
SELL_PRICE_INCREASE_PERCET = 1.005  
```

# Email Settings
Details: 

Email setting for low Bianance Balance & in case of Errors.
NOTE: For Sender Email always use GMAIL.
```
sender_email = "senderGMAILemailaddress"
receiver_email = "receiver1emailaddress", "receiver2emailaddress"
password = "senderemailpass"
```

# Currency Pair to Moniter on Binance
```
BINANCE_ASSET_TO_CHECK_1 = 'BTC'
BINANCE_ASSET_TO_CHECK_2 = 'USDT'
```
# Refresh Time Setting 3
Details: 

Refresh time to check Balance on Binance and report Low Balance via Email. Time in Seconds
```
REFRESH_TIME_BALANCE = 100
```
