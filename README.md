# Bitcoin-Price-Notifications

Bitcoin Price Notifications With Python
This is a Python app to get the price of Bitcoin gotten from the Coinmarketcap API.

This app uses the popular automation website IFTTT. IFTTT (“if this, then that”), a web service that bridges the gap between different apps and devices.

We created two IFTTT applets:

- One for emergency notification when Bitcoin price falls under a certain threshold; and
- the other for regular Telegram updates on the Bitcoin price

This Python app will make an HTTP request to the webhook URL which will trigger an action. 
This action could be almost anything you want. IFTTT offers a multitude of actions like sending an email, 
updating a Google Spreadsheet and even calling your phone.
