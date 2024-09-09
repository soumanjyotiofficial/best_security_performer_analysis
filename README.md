# Portfolio Performance Analysis

## Overview

In this project I have create an hypothetical project which invest on top 4 company in Banking , Pharma and IT sector. And analyzed  the best securities performed in the last three month.
## Project Structure

The portfolio is constructed based on the market capitalization of the sectors, and equal weight is given to the top four companies by market cap in each sector. The proportion of investment in each sector is determined by the market cap of the sector relative to the total market cap of all three sectors combined.

### Key Features

#### Sectorial Allocation

- **Banking**
- **Pharma**
- **IT**

#### Capital Allocation

- The total capital is distributed among the three sectors based on their market cap proportions.
- Equal investment is made in the top four companies by market cap within each sector.

#### Performance Analysis

- Historical data for the last three months is fetched for each stock.
- Cumulative returns are calculated to analyze the performance of each stock in the portfolio.
- The best-performing stock is identified based on the individual securities holding value.

### Technologies Used

- **Python**: Core language for data extraction, processing, and analysis.
- **pandas**: For data manipulation and analysis.
- **Plotly**: For data visualization and generating performance charts.
- **Fyers API**: To fetch historical data for stocks.

## Setup Instructions

### Prerequisites

- Python 3.x
- Required Python libraries: pandas, plotly, requests, pyotp
