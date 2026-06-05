# Bitcoin Market Sentiment vs Trader Performance

## Objective

The objective of this project is to analyze the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical trading data.

## Datasets

### Historical Trader Data

Contains trader-level information including:

* Account
* Coin
* Execution Price
* Trade Size
* Side
* Fee
* Closed PnL

### Fear & Greed Index

Contains daily market sentiment classifications:

* Extreme Fear
* Fear
* Neutral
* Greed
* Extreme Greed

## Methodology

1. Data Cleaning and Preprocessing
2. Date Alignment Between Datasets
3. Dataset Merging
4. Exploratory Data Analysis
5. Profitability Analysis
6. Trader Behavior Analysis
7. Correlation Analysis

## Key Findings

* Fear periods generated the highest cumulative trader profits.
* Extreme Greed periods showed strong profitability but higher volatility.
* Trading activity varies significantly across sentiment regimes.
* Top traders contribute disproportionately to overall profitability.
* Market sentiment can be a useful contextual signal for trading strategies.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Repository Structure

The repository contains the notebook, datasets, generated visualizations, summary statistics, and documentation.
