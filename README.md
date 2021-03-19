# algo_trading

To connect to Zerodha kite connect, have the following information
1. API Key
2. API Secret
3. UserID
4. Password
5. PIN

Using above information generate the next tokens
6. Request Token
7. Access Token

Install selenium and chrome webdriver to automate the process.


### Place order function api parameters
:param variety: regular, smo (after market order), bo (bracket order), co (cover order)
    :param exchange:
    :param tradingsymbol:
    :param transaction_type:
    :param quantity:
    :param product: CNC (cash and carry for equity), NRML (normal for F&O), MIS (Margin intraday squareoff for F&O)
    :param order_type: MARKET , LIMIT, SL (Stoploss), SL-M (Stoploss - market order)
    :param price:
    :param validity: DAY, IOC (Immediate or cancel)
    :param disclosed_quantity:
    :param trigger_price:
    :param squareoff:
    :param stoploss:
    :param trailing_stoploss:
    :param tag:
