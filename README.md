# Set Up:
## Google Colab:

## Locally:
- In local development, the necessary dependencies are listed in:
```bash
requirements.txt
```
.
To make sure the virtual environment is set up correctly using the default 
```bash
venv
```, 


# Analysis on commodity & security assets
All assets are aggregated in monthly average with USD as denomination currency

## Gold Data:

Period: 1/31/1978 - 10/31/2025

The monthly averaged LBMA Gold Price data is sourced from: https://www.gold.org/ which consolidates gold prices from Bloomberg, Datastream, ICE Benchmark Administration, World Gold Council

Fields: date, price


## Bitcoin Data:

Periods: 08/01/2010 - 11/01/2025

The monthly averaged Bitcoin Price data is sourced from: https://www.investing.com/crypto/bitcoin/historical-data

Fields: date, price, open, high, low, volume, percent_change


# Note:
- percent_change = open - price / open 