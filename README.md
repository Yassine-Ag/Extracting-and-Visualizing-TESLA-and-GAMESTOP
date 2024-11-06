
# Stock Data Extraction and Visualization

This Jupyter notebook guides you through extracting and visualizing stock data for Tesla and GameStop. It utilizes financial data libraries, web scraping techniques, and data visualization tools to demonstrate essential steps in data science projects involving stock and revenue data.

## Description

This project is designed to help individuals extract and visualize key financial data, allowing them to make informed decisions based on historical stock and revenue trends. The notebook covers the following steps:

- Extracting stock data from Yahoo Finance using the `yfinance` library.
- Scraping Tesla and GameStop revenue data from online sources.
- Cleaning and formatting the extracted data.
- Visualizing the stock data using a custom graphing function.

## Table of Contents

1. Define a Function to Create Graphs
2. Extract Tesla Stock Data (using `yfinance`)
3. Scrape Tesla Revenue Data (using `requests` and `BeautifulSoup`)
4. Extract GameStop Stock Data (using `yfinance`)
5. Scrape GameStop Revenue Data (using `requests` and `BeautifulSoup`)
6. Visualize Tesla Stock and Revenue Data
7. Visualize GameStop Stock and Revenue Data

## Prerequisites

To run this notebook, you will need the following libraries:

```python
import pandas as pd
import yfinance as yf
import requests
from bs4 import BeautifulSoup
import plotly.graph_objects as go
from plotly.subplots import make_subplots
```

Make sure to install any missing libraries before running the notebook.

## Usage

1. Clone this repository and navigate to the project directory.
2. Open the notebook in Jupyter Notebook or JupyterLab.
3. Follow the step-by-step instructions in each section to extract, process, and visualize the data.

## About the Authors

- **Joseph Santarcangelo** – PhD in Electrical Engineering, with expertise in machine learning, signal processing, and data science. Works for IBM.
- **Azim Hirjani** – Contributor to this project.

## License

This project is licensed under the IBM Skills Network.
