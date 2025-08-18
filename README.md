Multi-API Data Fetcher for Google Colab

Description

This repository contains a Python script designed for Google Colab environments to facilitate data fetching from various APIs. It integrates functionalities to retrieve data from:

•
Kaggle API: For accessing and downloading datasets.

•
Exchange Rate API: For current exchange rate information.

•
Alpha Vantage API: For stock and cryptocurrency data.

•
World Bank API: For economic indicators and development data.

This script is ideal for futere analysis, AI model training, researchers, data scientists, and developers who need to quickly access diverse datasets within a Google Colab notebook.

Features

•
Kaggle API Integration: Seamless setup and authentication for Kaggle, allowing dataset listing and downloading.

•
Multiple Data Sources: Fetches data from World Bank, Exchange Rate, and Alpha Vantage APIs.

•
Google Colab Ready: Designed to run directly in Google Colab, including files.upload() for Kaggle API key management.

•
Configurable: Easily set API keys and parameters for different data sources.

•
Pandas Integration: Fetched data is processed into Pandas DataFrames for easy manipulation and analysis.

Getting Started

Prerequisites

•
A Google Colab environment.

•
API keys for:

•
Kaggle

•
ExchangeRate-API (or use the free Frankfurter fallback)

•
Alpha Vantage



Installation and Usage

1.
Open in Google Colab: Upload the multi_api_data_fetcher.py script to your Google Colab environment or copy the code directly into a new Colab notebook.

2.
Kaggle API Setup: The script includes an interactive setup for the Kaggle API. When prompted, upload your kaggle.json file.

3.
Configure API Keys: Replace the placeholder API keys and parameters in the API CONFIG section of the script with your actual keys and desired settings:

4.
Run the Script: Execute the cells in your Google Colab notebook. The script will fetch data from the configured APIs and display initial results.

