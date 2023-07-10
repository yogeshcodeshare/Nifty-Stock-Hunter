# Nifty Stock Hunter: Automate Stock Selection For ShareGenius Swing Trading Method.

#### Part 1 :- Nifty 100 Stock Data Analysis and Selection Using Google Sheets and Yahoo Finance API

## Introduction:

    The Sharegenius Swing Trading Method by Mahesh Kaushik is a popular approach to trading in the stock market. It involves identifying stocks that have the potential to make significant gains over a short period of time, typically a few days to a few weeks. The method uses a combination of technical and fundamental analysis to identify these stocks.
    However, implementing the Sharegenius Swing Trading Method manually can be time-consuming and require a lot of effort. To overcome this, we aim to automate the process using Python, Google Sheets, and Angle API.
    The objective of this project is to fetch Nifty 100 stock data from Yahoo Finance, display it in a Google Sheet, and select stocks based on SST criteria. The script will run daily at 9 PM using a cron job, and the selected stocks will be added to the "Selected List" worksheet for further investment.
    In this way, we can save time and effort while implementing the Sharegenius Swing Trading Method and potentially increase the returns from the stock market.


## Objective:

    The objective of this project is to automate the Sharegenius Swing Trading Method by Mahesh Kaushik using Python, Google Sheets, Angle API.The aim is to fetch Nifty 100 stock data from Yahoo Finance and select stocks based on SST criteria. The script will run on Stock market Working days at 9 PM using a cron job, and the selected stocks will be added to the "Selected List" worksheet for futher investment.


## Methodology:

    1) Use Python and Yahoo Finance API to fetch Nifty 100 stock data.
    2) Create a Google Sheet using Google Sheets API to store the stock data.
    3) Analyze the data to select stocks based on CMP, 20-day high, and today's low. 
    4) Write a Python script to fetch stock data, compare it, and update the sheet. 
    5) Use formulas in Google Sheets to pick the selected stocks and display them in a separate worksheet.
    6) Set up a cron job to run the script on Stock market Working-days at 9 pm to update the selected stocks list.
    7)  Add error handling and logging to the code to handle exceptions.
    
## Potential technologies:

    - Python - for web scraping the stock data from Yahoo Finance and for implementing the logic to filter and compare the stock data.
    - Google Sheets API - for accessing and updating the Google Sheet that will store the stock data.
    - Pandas - for data manipulation and analysis of the stock data in Python.
    - Cron Job - for scheduling the Python script to run at a specific time every day to fetch the latest stock data.


## Deliverables:
    1) A Python script that fetches Nifty 100 stock data, compares it, and updates the Google Sheet.
    2) A Google Sheet that displays the stock data, selected stocks list.
    3) A cron job set up to run the script every day at 9 pm to update the selected stocks list.
    
    
### Potential Challenges:

    1) The Sharegenius Swing Trading criteria may need to be updated based on changes in the market or new research.
    2) The list of Nifty 100 stocks may change over time, requiring updates to the script to ensure accurate data is fetched.
    3) The Yahoo Finance API may change, requiring adjustments to the code to ensure data is extracted correctly.
    4)Error handling and logging may need to be updated to handle new exceptions that arise during web scraping and data processing.
    
    
