# Automate API Extraction Project

## Description
This project automates the extraction of cryptocurrency data from the CoinMarketCap API. It fetches the latest cryptocurrency listings, normalizes the data into a pandas DataFrame, and visualizes specific metrics using seaborn and matplotlib.

## Prerequisites
- Python 3.8+
- Anaconda (optional, but recommended for managing dependencies)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/automate-api-extraction.git
    cd automate-api-extraction
    ```

2. (Optional) Create and activate a virtual environment:
    ```bash
    conda create -n api-extraction-env python=3.8
    conda activate api-extraction-env
    ```

3. Install the required packages:
    ```bash
    pip install requests pandas seaborn matplotlib
    ```

## Usage
1. Obtain an API key from [CoinMarketCap](https://coinmarketcap.com/api/).

2. Replace the placeholder API key in the notebook with your own:
    ```python
    headers = {
      'Accepts': 'application/json',
      'X-CMC_PRO_API_KEY': 'your_api_key_here',
    }
    ```

3. Run the notebook to fetch and process the data.


# Movie Portfolio Project

## Description
This project involves analyzing a movie dataset to explore various metrics and trends within the film industry. It includes data cleaning, exploratory data analysis (EDA), and visualizations to derive insights.

## Prerequisites
- Python 3.8+
- Anaconda (optional, but recommended for managing dependencies)

## Usage
1. Ensure the movie dataset is in the correct path or update the notebook with the dataset's location.

2. Run the notebook to perform data cleaning, EDA, and visualization.
