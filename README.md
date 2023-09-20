# Python project for Data Engineering by IBM

Jupyter files are included

Firstly I webscraped largest banks by their market cap from:

https://web.archive.org/web/20200318083015/https://en.wikipedia.org/wiki/List_of_largest_banks


In the second task I extracted the information from a json and a csv file and removed unnecessary columns which I webscraped.

![extract](https://github.com/KarlJosephKumar/PythonDataEngineeringIBM/assets/41339304/79e02acf-ef81-4ecb-b4eb-1f9521e84ea7)

In the third task I transformed data on the bank list file.

Changed currency, names and decimals.

The user can provide a currency of their liking from the currencies available from the exchange_rates.csv files.

In case of a wrong currency or no value the currency will not be changed.

![transform](https://github.com/KarlJosephKumar/PythonDataEngineeringIBM/assets/41339304/3e0c25f0-f87c-4b9a-b135-675c60691f56)

Steps are logged into a logfile and a market cap csv file is created with corresponding name as: bank_market_cap_"Currency_chosen".csv
