# Investopedia-Trading
## Introduction
Investopedia Trading is a tkitner python program that's suitable for beginner who want to enter the trading world. First, Investopedia Stock Simulator is an excellent simulator 
that I always recommend for beginners due to its simplicity. Second, this program helps you automate your Investopedia trading game and take it to the next level. 
## What Does Investopedia Trading do?
Investopedia Trading asks you to enter the stocks you're interested in to calculate their expectancies (a measure to show which stocks are gonna make you more money and less risky).
It also shows you stock data to enable you to make decisoin. After you choose the stocks that you want to trade, you can execute the trade from the program automatically. Also, upon clicking "Execute trade", a new record on your notion database (trading journal) is added automatically.
## Necessary Prerequisites
First, in lines 52 and 53 in the scraping.py file, you got to replace `creds.username` and `creds.password` with your Investopedia's email and password.
Second, you got to add uBlock Origin (chrome extension) files to the program directory. To do that:
1. Add uBlock Origin as an extension on chrome shorturl.at/qvCLM
2. Now assuming you are on windows, go to 'C:\Users\YOUR_USER_NAME\AppData\Local\Google\Chrome\User Data\Default\Extensions\cjpalhdlnbpafiamejdnhcphjbkeiagm'
3. There should be a folder with a number (the version number). Copy that folder and paste it in the program directory.

## How to Use Investopedia Trading?
Upon running the program, you get this window which asks you about the **risk percentage**: how much of your cash are you ready to lose on a single trade? Risk percentage is often 2% for people with much cash. People with less cash tend to increase it to 5%. If you uncheck 2%, you can enter your own risk percentage. Secondly, the program will ask you about the chance of winning which set by default to 0.9 to all stocks. If you uncheck it, you'll have to enter winning chance to each individual stock. Thirdly, below the two checkboxes you'll find thee account value and cash. These values are scraped from your Investopedia profile.

![image](https://user-images.githubusercontent.com/40627412/135750345-24be1cf0-889d-4085-a896-03318fb0a248.png)

Then, you'll ahve this window for each stock that you're interested in. The first entry is for the ticker (symbol) of the stock. The second is for the target price (what price you want the stock to reach). The third entry is for the stop loss price (the price at which you accept your loss and exit the trade.) If you've got more stocks that you're intersted in, then you can press "Onto the next stock" button. If this is the last stock, then you can press "finish" to display the results.

![image](https://user-images.githubusercontent.com/40627412/135750914-2b92c67f-d3f7-4b67-91a0-84b03a4dcb7b.png)
