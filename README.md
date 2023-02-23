# ExchangeRate-FixerIO-Mendix-9

### 150+ Live Country Currency Exchange Rates

This module utilizes the APIs provided by API Layer to enable live currency conversion for 170 countries using fixer.io

# Dependencies:
•	Mendix Modeler 9.18.4

•	API Layer (https://apilayer.com/)- API Key


## Configuration:
•	Create an account on the API Layer (https://apilayer.com/ ) and subscribe to the fixer currency category from the API Layer marketplace (https://apilayer.com/marketplace/category/currency) (https://apilayer.com/marketplace/fixer-api) 

•	Collect the API Key for your API Layer account

•	Add the API Key value to the constant APIKey from the module

•	Add the ExchangeRateCurrency_Overview to the navigation

•	Run the application and navigate to the Exchange Rate Currency Overview page then click on Currency Codes tab and press on the button Sync Country Code to retrieve all the country currency codes and country names

•	Once the currency codes have been saved in the table, you can use the conversion feature to convert the currency rates on the convert tab 

•	You can also use the exchange rates conversion feature to obtain the latest rates for the multiple currency codes from the base currency code


*NOTE: The ‘CurrencyConversion’, ‘LatestCurrencyDiff’, and ‘SupportedSymbols’ folders contain integrated APIs that retrieve all the country codes, perform currency exchange conversion, and compare conversions using multiple currency codes 
