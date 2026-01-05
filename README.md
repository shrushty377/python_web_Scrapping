Amazon Web Scraping Project using Python

Project Overview
This project demonstrates web scraping of Amazon product data using Python. The script uses the Requests library to send HTTP requests and BeautifulSoup to parse HTML content and extract meaningful product information. The collected data can be used for analysis, comparison, or stored for further processing.

Technologies Used

Python

Requests

BeautifulSoup (bs4)

Pandas (optional, for data handling)

Features

Sends browser-like headers to avoid request blocking

Scrapes product details such as:

Product Name

Price

Ratings

Number of Reviews

Product URL

Handles missing or unavailable values safely

Stores extracted data in CSV or Excel format

Easy-to-read and modular code structure

Use Cases

Price comparison and market analysis

Product trend analysis

Learning real-world web scraping techniques

Data collection for analytics and visualization projects

Disclaimer
This project is created for educational purposes only. Scraping Amazon may violate their terms of service. Use responsibly and avoid making frequent or automated requests.

Project Structure
amazon_web_scraper/

amazon_scraper.py

requirements.txt

output.csv

README.md

How to Run

Install the required libraries
pip install requests beautifulsoup4 pandas

Run the script
python amazon_scraper.py

Author
Shrushty Vandre
GitHub: https://github.com/shrushty377

LinkedIn: https://linkedin.com/in/shrushty-vandre-7a9175237
