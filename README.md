# Web Crawler for Cryptocurrency Prices using Selenium

## Overview
This project involves creating a web crawler to collect and analyze cryptocurrency price data from the Messari website. The collected data is stored in an Elasticsearch database and visualized using Kibana. The project demonstrates web scraping, data processing, and visualization techniques.

## Steps

### 1. Data Collection
- **Objective**: Crawl the cryptocurrency information from the Messari website.
- **Tools**: Selenium for web crawling, Elasticsearch for data storage.
- **Tasks**:
  - Crawl the data for thousands of cryptocurrencies displayed on the website.
  - Save the data in an Elasticsearch database based on their tags.

### 2. Data Sorting
- **Objective**: Sort the prices of each cryptocurrency.
- **Tasks**:
  - Sort the prices in descending order.

### 3. Trend Analysis
- **Objective**: Analyze the price trend of each cryptocurrency over the past month.
- **Tasks**:
  - Store the information based on the price trend (increasing or decreasing percentage).

### 4. Volume Calculation
- **Objective**: Calculate the trading volume of each cryptocurrency.
- **Tasks**:
  - Store the cryptocurrencies based on their trading volume in descending order.

### 5. Data Visualization
- **Objective**: Visualize the stored data.
- **Tools**: Kibana for visualization.
- **Tasks**:
  - Install Kibana.
  - Show the collected data graphically using Kibana.

### 6. Creative Approach
- **Objective**: Ensure simple and efficient access to the data.
- **Tasks**:
  - Develop a creative approach to manage and access the large amount of data available on the internet.

### 7. Export Data
- **Objective**: Export the collected data.
- **Tasks**:
  - Export the data and include it in the final report.

## Requirements
- Python 3.x
- Libraries: Selenium, Elasticsearch, Kibana, pandas

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Set up Elasticsearch and Kibana.
4. Run the provided Python scripts to:
   - Crawl the data using Selenium.
   - Process and store data in Elasticsearch.
   - Visualize the data using Kibana.

## Results
- Sorted and analyzed cryptocurrency price data.
- Graphical representation of the data trends and volumes using Kibana.

## Conclusion
This project demonstrates web crawling using Selenium, data processing and storage using Elasticsearch, and data visualization using Kibana. It provides insights into cryptocurrency price trends and volumes.

