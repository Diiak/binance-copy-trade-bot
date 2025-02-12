# binance-copy-trade-bot 

This trading bot is designed to replicate the transactions of choosen traders on your Binance Futures or Bybit account. It connects to your account via the API and automatically executes transactions based on trading signals generated by professional traders.

### Features
- Compatible with Binance Futures and Bybit 
- Copy the transactions of skilled traders
- Rapid and simple setup
- Launcher to setup the bot
- Automated trading
- Regular updates

### Prerequisites
- Python 3.8 or higher
- A Binance Futures or Bybit account
- API key and secret key for your account (please do not share this information)

### Database Setup
Follow the instructions in https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-ubuntu/ to set up MongoDB on the same host where the program is run.  
Follow https://www.digitalocean.com/community/tutorials/how-to-secure-mongodb-on-ubuntu-20-04 to set up username and password.  

OR

Create an account online and copy/paste your cluster link (for Binance API version) during the setup.

### Software setup 
1. Clone the GitHub repository using the following command:
`git clone https://github.com/tpmmthomas/binance-copy-trade-bot.git`
2. Go to the directory of the exhange you are using (Bybit or Binance) and install the necessary dependencies by running :
`pip install -r requirements.txt`

### Usage
1. Execute the "launcher.py" file located in the project's root directory using the following command:
`python launcher.py`
2. The launcher will prompt you to choose between the Binance and Bybit exchanges.
3. Follow the launcher's instructions to configure the bot. You may also configure additional options depending the desired exchange.
4. Once setup is complete, the bot will begin copying and applying the trades of designated traders to your account.

### Warnings
- The purpose of this trading bot is to help you replicate the transactions of professional traders. It does not, however, guarantee profits, nor is past performance indicative of future performance.
- Futures trading carries substantial financial hazards. Utilize this bot at your own peril, and only invest what you can afford to lose.


### Disclaimer
USE THIS SOFTWARE AT YOUR OWN RISK. THE AUTHORS ASSUME NO RESPONSIBILITY FOR YOUR TRADING RESULTS.     


### Buy Me A Coffee
You could support my developement by using my refferal code at Bybit Trading platform. I highly recommend it.
https://www.bybit.com/en-US/invite?ref=L9QLLJ  

Good luck and successful trading!

Donations are also welcome at the following addresses:

BTC: bc1qx9sldvfqsggajdhc24pvflcyl5x4lrc75303xq
USDT (ERC20/BSC): 0xb5bb89624842E3De8FC9e5F6dC2b3951d91f7dBa
ATOM: cosmos132v3ud437dvelw79xhe3pnned7nrzkvy8cespd
