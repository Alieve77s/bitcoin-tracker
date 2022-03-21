# bitcoin-tracker
A Python script that will fetch the price of BTC every 5 min, and if below the threshold or above a certain price, will send a msg to Telegram bot.

To get this script to work, you will need the following things:

    1. A coinmarketcap.com API key. Because we are going to make use of their API to get the latest bitcoin price.
    2. The telegram app, and your account’s chat_id.
    3. Then a telegram bot and it’s token key. (Without a bot, you will not be able to send programmatic messages). 
    
If you need some help getting the above info follow these directions:

    1. Coinmarketcap.com no longer provides cryptocurrency data for anonymous users. So we need an API key to use their service. Then first do signup or login (at coinmarketcap.com). When you do so you will be taken to your account dashboard. Now you can get that by clicking on that COPY KEY button which will pop up when you hover over that API Key box. You can see with the basic account we get 333 free requests a day and thats plenty!
    
    2. Before continuing this step, please make sure you have the Telegram app installed on your mobile phone/computer and you have an account created. Go to    contacts, and in the search bar type: 'IDBot'.  Get that bot and '/start' it. You should get your Telegram chat_id.
    
    3. Create a Telegram Bot using 'BotFather' (if your unsure how to complete this step, Google: 'Creating Tele Bot with BotFather' and follow instructions.    When finished, take note of the Bot's Token.
    
    NOW THAT YOU HAVE YOUR [API_KEY], YOUR [BOT_TOKEN], AND [CHAT_ID]. PLUG THEM INTO THE 'CONSTANTS' VARIABLES AT THE TOP OF THE SCRIPT.

Let script run on a server, or in the background of your OS. https://www.pythonanywhere.com is another resource for running python scripts. 
