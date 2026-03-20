# Stock Market Visualization and Analysis

A Jupyter notebook for exploring and analyzing stock market data with interactive visualizations.

## Overview

This project analyzes historical stock market data for cybersecurity companies and major market indices. Insights were made regarding the visualizations to answer the question of whether Crowdstrike's stock should be invested in over its competitors and benchmark indices. The notebook provides tools for data exploration, analysis, and visualization of price trends and trading volume patterns.

## Files

- **`stocks.ipynb`** - Main Jupyter notebook containing data analysis and visualizations
- **`stocks.csv`** - Historical stock market data (CSV format)
- **`index.html`** - Exported interactive visualization (generated from notebook)

## Data

The dataset includes daily stock price data containing:
- **Date** - Trading date
- **Symbol** - Stock ticker symbol (CRWD, FTNT, PANW, ZS, ^GSPC, ^IXIC)
- **Open** - Opening price
- **High** - Highest price of the day
- **Low** - Lowest price of the day
- **Close** - Closing price
- **Volume** - Number of shares traded

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook, JupyterLab, or Google Collab
- Required libraries: pandas, matplotlib, seaborn, numpy, jupyter

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Jgorf/Stock-Market-Visualization-and-Analysis.git
cd Stock-Market-Visualization-and-Analysis
```

2. Install dependencies:
```bash
pip install jupyter pandas matplotlib seaborn numpy
```

3. Launch Jupyter:
```bash
jupyter notebook
```

4. Open `stocks.ipynb` and run the cells

## Features

- **Price Analysis** - Explore opening, closing, high, and low prices
- **Volume Analysis** - Analyze trading volume trends
- **Multi-Symbol Comparison** - Compare performance across different stocks
- **Time Series Visualization** - Interactive plots of stock movements
- **Statistical Summaries** - Descriptive statistics for each symbol

## Usage

1. Load the notebook in Jupyter or VS Code with the Jupyter Extension
2. Run cells sequentially to load and explore the data
3. Modify parameters to analyze different date ranges or symbols
4. Generate visualizations to identify trends and patterns

## Symbols Analyzed

- **CRWD** - CrowdStrike Holdings
- **FTNT** - Fortinet
- **PANW** - Palo Alto Networks
- **ZS** - Zscaler
- **^GSPC** - S&P 500 Index
- **^IXIC** - Nasdaq Composite Index

## Contributing

Contributions are welcome! Feel free to:
- Report bugs or issues
- Suggest new analysis features
- Improve visualizations
- Expand the dataset

## License

This project is open source and available under the MIT License.

## Support

For questions or issues, please create a GitHub issue in this repository.
