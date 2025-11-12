# Set Up:
## Google Colab:


## Locally:
Since the folders are all in place, the only necessary step is to install the dependencies for scripting. These dependencies are listed in: `requirements.txt`.
To make sure the virtual environment is set up correctly (with the default `venv` folder):

1. Make sure you are under the root directory and run the following to create your virtual environment:
```bash
python -m venv venv
```
2. Once the `venv` directory has been set up, run the virtual environment:
```bash
source venv/bin/activate
```
3. Once the virtual environment has been activated, make sure the notebook's kernel is using the current venv environment.


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