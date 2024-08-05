# Zillow Rental Property Scraper

This project scrapes rental property data from a Zillow clone website and fills out a Google Form with the scraped data using Selenium. The project is divided into two parts:

1. **Scraping the rental property data (links, addresses, prices)**
2. **Automating the data entry into a Google Form**

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine
- Google Chrome browser installed
- ChromeDriver compatible with your Chrome browser version
- Python packages: `selenium`, `beautifulsoup4`, `requests`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/zillow-rental-scraper.git
    cd zillow-rental-scraper
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Download the ChromeDriver from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads) and place it in your project directory or any directory included in your system's PATH.
This project is open-source and available under the [MIT License](LICENSE).
