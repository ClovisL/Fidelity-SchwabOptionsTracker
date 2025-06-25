https://colab.research.google.com/github/ClovisL/FidelityOptionsTracker/blob/main/FidelityOptionsTracking.ipynb

### A Python script utilizing Pandas that reads a CSV file from Fidelity of trading history, creates a dataframe of only options trades, and exports an excel file.

The transaction date, ticker, whether it was a call/put, expiration date, strike price, quantity, and total $ amount are filtered and added to a new data frame to export into an excel spreadsheet, where further analysis through pivot tables may be done, or it can be imported into a dashboard.

I wrote this program to better help me keep track of my trade history through a more convenient format than what is available through Fidelity's website, allowing me to view my past performance based on ticker and types of trades.


### Version of the code for Schwab CSV files:
https://colab.research.google.com/drive/1p1Mbvvkc2rEG7hJlnpSpSrq-0YcMQAKg?usp=sharing


### I also created a Looker dashboard to visualize charts and tables using the Excel file. Using the following link, and with a Google account, you can import your own data in the form of a Google Sheets file saved in your Google Drive into it for visualization:
https://lookerstudio.google.com/reporting/bee4f806-cf0a-47e7-afd3-63c688969c21/preview

* First, you will use this options tracker Colab notebook to format the CSV file downloaded through Fidelity into a .xlsx file.
* Upload the spreadsheet into your Google Drive, open it and save it as a Google Sheets file, so it can be imported into the Looker Dashboard. The .xlsx file will not be needed afterwards.
* If you have multiple files across different dates, or want to continuously add more recent information, you can click the following link for instructions on importing one Google Sheets file into another: https://support.google.com/a/users/answer/9308940?hl=en
* Open the link to the Looker dashboard, and you can import your own data and edit as needed. Many of the metrics and settings will need to be fixed to work with a new data source, as Looker will have issues even with an exact copy of the data source used.
