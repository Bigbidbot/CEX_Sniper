# Cex Sniper Bot 
This is the first bot (Sniper) that buys tokens when listed on centralized exchanges (as Binance, MEXC (temporary don't work), OKEX, HUOBI and Gate.io).

Latest version link
( https://github.com/Bigbidbot/CEX_Sniper/releases )

## Bot setup

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++

YOUTUBE INSTRUCTION (https://youtu.be/xF8EgsO0mlA)

Telegram group (https://t.me/bigbidbotmarketinggroup) 
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1. Installing the Bot (only for Windows). Download and unzip file and place it in a folder on your computer.
2. Open the configuration file (**settings_user.txt**) in a text editor like Notepad
### Parameters:
  - "**exchange_name**": Next, choose an exchange (the name of the exchange is written in capital letters).  At the moment there are only five. `Like: MEXC(temporary don't work), BINANCE, GATEIO,  OKEX, HUOBI, KUCOIN`
  - "**token_name**": Enter the name of the token (as it is called on the exchange) `Like: GMT`
  - "**accountId_huobi**":  How to get it and fill it out, see our YouTube channel.
  - "**amount_pay**": Enter the amount in USDT - for which the order will be placed   `(Keep in your wallet only the amount that you are willing to spend on this listing)` `Like: 20`
  - "**price_buy**": Set the maximum purchase price of the token `Like: 0.1`
  - "**price_sell**": Set the maximum sale price of the token `Like: 0.5`
  - "**AUTOPRICE**": _Boolean_ (True or False) after the start of trading, the bot calculates the optimal price and sets its price. The difference in the purchase price and the sale price in the PERCENTPROFIT parameter (for example 20), enabling the mode parameter AUTOPRICE":"True". In this mode, the start time of the auction starts automatically placing orders. (Dont WORK Binance and KUCOIN)
  - "**PERCENTPROFIT**":  `Like: 20`
  - "**secret_key**": Specify your license key or if you are testing, specify "1111111111" `Like: c2d2f5gq2f`
  - "**FUNDPASS**": The password that the GATEIO requests. You can enter it manually in windows chrome. But sometimes because of this there are failures in the purchase.
  - "**TYPESTOPLOSS**": _IDO_ or _SECOND_. IDO - the coin has not yet been sold anywhere and strong variations in price are possible. The SECOND - the coin has already been on another platform and we understand its estimated price.
  - "**STOPLOSSORDERS**": _Boolean_ (True or False). Enable or disable the purchase mode by the trigger system. Those the order is not placed until the price is determined in our order. Study trigger orders ( https://www.huobi.com/support/ru-ru/detail/900001857066 )
  - "**MAXXPRICE**": _Integer_. Is the divisor that divides your "price_buy". It is equal to "6" for the SECOND, or is taken from the settings for IDO. 
Those if you have specified the maximum price ("price_buy") of 12 dollars and the SECOND type in "TYPESTOPLOSS". That will be placed orders with a purchase price of 100% 90% 80% 70% 60% 50% from 12 dollars i.e. 12, 10.8, 9.6, 8.4, 7.2, 6 dollars price. 
If this is the IDO mode, then from 12 dollars and "MAXXPRICE":6 the prices will be divided by from 1 ...... to 6 i.e. 12, 6, 4, 3, 2.4, 2 dollars. And in this mode ("STOPLOSSORDERS": "True"), we are trying to sell at a higher price. Your sale price ("price_sell") adds 20% 6 times. Those 100% 120% 140% 160% 180% 200% from "price_sell"
  - "**YEAR, MONTH, DAY, HOUR, MINUTE, SECONDS**" Enter the listing start date and time, according to your local time (not UTC) (all values up to 10 are specified without 0) `Like: 2022 4 9 15 00 00`
3. _A very important parameter_, be sure to synchronize the time in advance in your computer settings
4. Go into the unzipped folder. In the folder, push "Shift" on your keyboard, then do a right-click mouse. Click on "Open command windows here" or "Open Powershell windows here"
5. Run the bot in command shell (".\BBB_CEX_Sniper.exe") and wait for the browser to open, then follow the instructions in the window  command shell
**You need to make a fake order with a matic to bypass protection against bots.**
-	_BROWSER CHROME_: Login in CEX in browser
-	_COMMAND SHELL_: and press "Enter" in command shell
-	_BROWSER CHROME_: wait Load MATIC page
-	_BROWSER CHROME_: CHANGE INTERFACE TO ENGLISH
-	_COMMAND SHELL_: press ENTER
-	_BROWSER CHROME_: Input price matic 0.1 USDT and amount 100  
-	_COMMAND SHELL_:   Press "ENTER" so that the bot clicks the green button for you and make a test purchase
-	THEN THE COUNTDOWN WILL GO ON THE COMMAND SHELL  and orders will be placed during the listing
- _COMMAND SHELL_: Have you finished trading? Close browser? Press "Enter" if YES (after pressing enter the browser will stop working)
-	_COMMAND SHELL_: If need: Ctrl+C emergency pressing

## Security questions
There is a lot of deceit and fake in blockchain. What can we do to trust each other?
- Our telegram channel is open for messages between clients without moderation. Fraudsters don't do that.
- Create a new CEX-exchange account
- Enter by QR code
- Enable two-factor authentication
- Money only for listing
- Run the bot on a dedicated server or virtual machine, or as a guest user on your computer Windows
- All certificates and requests will be stored in the bot folder so that you can see that everything is fine
- The version of the chrome browser on the local computer must match the version of chromedrive.exe (https://chromedriver.chromium.org/downloads)


## P.S.
-	trading takes place only in USDT
-	sometimes the antivirus can block the browser. Install the certificate **ca.crt** to the trusted root.
-	the bot is forbidden to resell and transfer, running more than three times at the same time will block your bot ( money is not returned)
there are no analogues of our bot
-	_we sell no more than one hundred licenses_
-	it is desirable to do active actions in 10 minutes of the listing (buy, sell, click on the pages).
-	our team is also developing similar scripts. Send DM telegram @bigbidbotsupport	


## How to buy our bot
- **You can test our bot for free**. The test key is written to the configuration files. It only trades in MATIK coin.
When you start the bot, a wallet will be indicated on which you will need to make a payment, after that we ask you to write to us in a telegram to receive a key (license).

- **You can test our bot for 50$ / 4 days - Full-slow (0.3 sec/check) version**. For example, if you want to play with only 1 listing

- **Price 150$** Full-fast (0.1 sec/check) version  (USDT, BUSD - BEP20) 0x5a8d789C4cf0fa171230cCAd008CbAb942C96EA9 and DM telegram @bigbidbotsupport
