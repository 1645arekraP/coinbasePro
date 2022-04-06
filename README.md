# CoinbaseProNotis
Because Coinbase Pro does not offer notifications, and I forget to check my account, I have started this project to help with my Python and FLask skills. The goal is to have Twilio SMS bot to send the user updates on their portfolio. I'm still figuring out what I want to send and how I want it to look, but right now it sends all Cryptocurrencies in a Coinbase Pro portfolio, and the USD price of the Crypto Coin along with the total portfolio worth. Texts are sent every 30 minutes.

# Version 1.1.2
- Cleaned up more spaghetti code
- Started time function to send timed texts (Plan to finish it within Flask)
- Started Flask website that will be hosted on Heroku

# Version 1.1.1
- Cleaned up some spaghetti code
- Added KeyError handling for Crypto Currencies being converted to USD

# Version 1.1
- Protected some variables
- Fixed price formatting
 
# To Do list
- Add twilio conversations that expand a currencies info
- Fix the spaghetti code
- Include Open Orders
- Create a webapp using Flask framework
- Add timed code execution
