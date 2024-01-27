# Web Scraping COVID-19 Data from Worldometer

This Python script scrapes COVID-19 data from the Worldometer website and saves it to a CSV file. It utilizes the `requests` library to fetch the HTML content of the webpage and `BeautifulSoup` for parsing the HTML and extracting relevant data.

## Requirements

- Python 3.x
- pandas
- requests
- BeautifulSoup4

## Installation

Make sure you have Python installed on your system. You can install the required libraries using pip:

```bash
pip install pandas requests beautifulsoup4
```

## Usage

1. Clone or download the script to your local machine.
2. Open a terminal or command prompt and navigate to the directory containing the script.
3. Run the script using the following command:

   ```bash
   python your_script_name.py
   ```

   Replace `your_script_name.py` with the name of your Python script file.

4. The script will scrape the COVID-19 data from the Worldometer website, process it, and save it to a CSV file named `Corona_Dataset.csv` in the same directory.

## Handling Null Values

The script automatically handles null values encountered during the scraping process. Pandas DataFrame is used to represent the scraped data, and it provides various methods for handling missing data, such as dropping rows with null values or filling them with appropriate values.

## Conversion to CSV File

The scraped data is converted to a CSV file named `Corona_Dataset.csv`. 
