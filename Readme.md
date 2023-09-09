# Article Scraper

This Python script scrapes the text content of a Medium article from a given URL and stores the extracted text in a file.

## Prerequisites

Before running the script, make sure you have the following libraries installed:

- [Requests](https://pypi.org/project/requests/): `pip install requests`
- [Beautiful Soup](https://pypi.org/project/beautifulsoup4/): `pip install beautifulsoup4`

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/article-scraper.git
   cd article-scraper
2. Run the Python script:
   ```bash
   python python_scrapper.py
3. You will be prompted to enter the URL of the Medium article you want to scrape. Make sure the URL is in the following format:
   ```bash
   https://medium.com/@author/article-title-1234567890
4. The script will then fetch the article's content, remove HTML tags, and save it in a text file in the scraped_articles directory. The file will be named after the article's title.
5. The saved file can be found in the scraped_articles directory.
## Example:
- To test the script, you can use the following Medium article URL:
  ```
  https://medium.com/@subashgandyer/papa-what-is-a-neural-network-c5e5cc427c7
### Note
1. This script is specifically designed for scraping Medium articles. Make sure to provide valid Medium article URLs.
2. Please respect copyright and licensing terms when using this script.

**Happy scrapping!** 🙂
   
