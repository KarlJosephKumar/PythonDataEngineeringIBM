# Python project for Data Engineering by IBM

Jupyter files are included

Firstly I webscraped largest banks by their market cap from:

https://web.archive.org/web/20200318083015/https://en.wikipedia.org/wiki/List_of_largest_banks


In the second task I extracted the information from a json and a csv file and removed unnecessary columns which I webscraped.

![extract](https://github.com/KarlJosephKumar/PythonDataEngineeringIBM/assets/41339304/5c94b6b5-53ed-46fc-b7ae-35b77f49428a)

In the third task I transformed data on the bank list file.

Changed currency, names and decimals.

The user can provide a currency of their liking from the currencies available from the exchange_rates.csv files.

In case of a wrong currency or no value the currency will not be changed.

![transform](https://github.com/KarlJosephKumar/PythonDataEngineeringIBM/assets/41339304/9376bdff-3be5-4a1b-a8b0-8e1096e6ccc2)

Steps are logged into a logfile and a market cap csv file is created with corresponding name as: bank_market_cap_"Currency_chosen".csv
