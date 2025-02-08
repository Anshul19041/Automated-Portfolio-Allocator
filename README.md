# Investment Strategies using Python

## Overview

This repository contains two quantitative investment strategies implemented in Python:

Equal-Weight S&P 500 Index Fund - A strategy to create an equally weighted portfolio of all S&P 500 stocks.

Quantitative Momentum Strategy - A strategy that selects the top 50 momentum stocks and allocates capital equally among them.

## 1) Equal-Weight S&P 500 Index Fund

### Description

Unlike traditional market cap-weighted indices, this strategy allocates an equal proportion of capital to each stock in the S&P 500.

### Features

Fetches the latest S&P 500 stock list

Calculates the equal-weight allocation for a given portfolio size

Exports recommendations to an Excel file

### Technologies Used

Python Libraries: NumPy, Pandas, Requests, XlsxWriter, Math

Data Processing: Fetching stock data, performing allocations

Output: Generates an investment plan in a structured Excel format



## 2) Quantitative Momentum Strategy

### Description

This project implements a momentum-based investment strategy, selecting the top 50 stocks with the highest price momentum and calculating equal-weight portfolio allocations.

### Features

Identifies high-momentum stocks based on recent price trends

Allocates an equal-weight portfolio of the top 50 stocks

Exports recommended trades to an Excel file

### Technologies Used

Python Libraries: NumPy, Pandas, Requests, XlsxWriter, SciPy

Momentum Calculation: Uses statistical methods for ranking stocks

Data Processing: Fetches stock lists and historical prices

