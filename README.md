# Sephora-Webscraping-Tool

A Python script to track the price of a specific Sephora product and log the data daily into a CSV file. This tool uses web scraping to extract product details like the name, price, and the date of the price check, and appends them to a dataset for easy monitoring.

Features:
- Automated Web Scraping: Retrieves the product name and price daily from Sephora's website.
- Data Logging: Appends the product name, price, and the current date into a CSV file for tracking over time.
- Email Alerts (Optional): Ready to be extended for email notifications when the price changes.
- Daily Updates: Runs continuously, checking the price every 24 hours.

## How It Works

**1. Libraries Used:**

- BeautifulSoup: Parses and extracts the relevant product details from the webpage.
- Requests: Sends GET requests to fetch the HTML content of the product page.
- Datetime: Captures the current date.
- CSV: Logs the product details into a CSV file.
- smtplib: Placeholder for email notifications (not implemented in this version).

**2. Workflow:**
- The script scrapes the product page for the name and price.
- Organizes and stores the data into a CSV file (Sephora Webscraper dataset.csv).
- Continuously runs in a loop, checking and appending price data every 24 hours.
