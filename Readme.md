# Pendle Finance Data Analysis and Visualization

This Python script analyzes and visualizes data from the Pendle Finance API, focusing on asset prices, trading volumes, and APY (Annual Percentage Yield) metrics.

## Features

1. **Data Retrieval**: 
   - Fetches asset data from Pendle Finance API
   - Retrieves OHLCV (Open, High, Low, Close, Volume) data for specific assets
   - Collects APY history for specified markets

2. **Data Processing**:
   - Converts raw API data into pandas DataFrames
   - Calculates PT (Principal Token) prices from YT (Yield Token) data
   - Resamples data to different timeframes (e.g., hourly to daily)

3. **Technical Analysis**:   
   - Calculates Exponential Moving Averages (EMA)

4. **Visualization**:
   - Creates interactive candlestick charts for YT and PT prices
   - Generates volume charts
   - Produces APY charts showing Implied APY, Underlying APY, and EMA

5. **Output**:
   - Saves charts as interactive HTML files
   - Displays charts in the notebook environment

## Key Components

- **Asset Data Retrieval**: Fetches and processes asset data from Pendle Finance API.
- **OHLCV Data Analysis**: Analyzes Open, High, Low, Close, and Volume data for specified assets.
- **APY Analysis**: Retrieves and visualizes APY history for specified markets.
- **Chart Creation**: Utilizes Plotly to create interactive financial charts.

## Usage

Run the script in a Jupyter notebook environment. Ensure you have the required libraries installed (pandas, numpy, plotly, requests).

The script will generate HTML files containing interactive charts, which can be viewed in a web browser.

## Note

This script is designed for analysis and visualization of Pendle Finance data. It's not intended for financial advice or trading decisions.