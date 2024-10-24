# Social Media Scraping Tools

This repository contains various Jupyter notebooks for scraping data from popular social media platforms using Python. The scripts demonstrate how to collect data from Twitter, YouTube, and Instagram, as well as general web scraping techniques.

## Notebooks

1. **TwitterScrapping.ipynb**
   - A Python-based Twitter scraper that utilizes the Twitter API to collect tweets and user information.
   - Ensure you have the necessary API keys to run this notebook.

2. **YoutubeScrapping.ipynb**
   - A tool for scraping video information, comments, and user data from YouTube.
   - Requires Google API credentials for full functionality.

3. **instagramScrapper.ipynb**
   - A scraper designed to extract data from Instagram profiles.
   - Created using Google Colab; ensure you have the necessary libraries installed.

4. **webScrapper.ipynb**
   - A general-purpose web scraper that can be adapted for various websites.
   - Demonstrates the use of libraries like BeautifulSoup and Requests.

5. **webScrappingDataToCsv.ipynb**
   - This notebook shows how to save the scraped data into a CSV file for easy analysis and storage.
   - Can be used in conjunction with the web scraper.

## Requirements

- Python 3.x
- Libraries:
  - `requests`
  - `BeautifulSoup4`
  - `pandas`
  - `tweepy` (for Twitter)
  - `google-api-python-client` (for YouTube)

You can install the required libraries using pip:

```bash
pip install requests beautifulsoup4 pandas tweepy google-api-python-client
