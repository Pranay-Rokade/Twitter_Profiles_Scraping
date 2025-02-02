# Twitter_Profile_Scraping

## Overview
This project automates the process of scraping Twitter profile data using Python and Selenium. It extracts information such as bio, follower count, following count, location, and website from a list of Twitter profiles.

## Features
- Automated scraping of Twitter profiles
- Handles missing data gracefully
- Saves extracted data into a structured CSV file
- Uses Selenium WebDriver for browser automation

## Prerequisites
Before running the script, ensure you have the following installed:

- Python (>=3.7)
- Google Chrome or Mozilla Firefox
- WebDriver Manager (`webdriver_manager` Python package)

## Usage
1. Prepare a CSV file (`twitter_links.csv`) containing the Twitter profile URLs, each on a new line.
2. Run the file.
3. The extracted data will be saved as `Scraped_Twitter_Data.csv`.
