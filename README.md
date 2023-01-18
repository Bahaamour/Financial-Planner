# Financial-Planner
![An image for the header of the Repository](/Images/Financial_planning.png)

This project help credit union members evaluate their financial health by:

1. Giving them the ability to assess their monthly budget.
2. They'll be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds.

## Technologies
This platform uses python 3.7.13 with the following libraries:


`Pandas`

`os`

`json`

`requests`

`dotenv`

`alpaca_trade_api`

---
## Installation Guide

To install `pandas` and `numpy` libraries, run the following code in your terminal 

```python
pip install pandas

pip install numpy
```

To intsall `requests` and `json` libraries, run the following code in your terminal. Ensuring that your development environment is activated before running the code:

For activating your development environment.

```python
conda activate dev
```

For Request library.

```python
conda install -c anaconda requests
```

For Json library.

```python
conda install -c jmcmurray json
```

In order to interact with APIs a `python-dotenv` library and ALPACA SDK needs to be installed.

```python
pip install python-dotenv
```

```python
pip install alpaca-trade-api
```


---

## Usage 

User needs to follow the Monte Carlo Simulation guides below: 

```python

Init signature:
MCSimulation(
    portfolio_data,
    weights='',
    num_simulation=1000,
    num_trading_days=252,
)
Docstring:     
A Python class for runnning Monte Carlo simulation on portfolio price data. 

...

Attributes
----------
portfolio_data : pandas.DataFrame
    portfolio dataframe
weights: list(float)
    portfolio investment breakdown
nSim: int
    number of samples in simulation
nTrading: int
    number of trading days to simulate
simulated_return : pandas.DataFrame
    Simulated data from Monte Carlo
confidence_interval : pandas.Series
...
    Number of trading days to simulate. DEFAULT: 252 days (1 year of business days)
File:           ~/Desktop/Financial-Planner/MCForecastTools.py
Type:           type
Subclasses:     
```

---
## Contributors

Baha Amour
---

## License

MIT.