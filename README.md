#JustWatch Web Scraper#
###Project Overview###
This project is a web scraper designed to extract movie and TV show information from JustWatch (https://www.justwatch.com). It collects data for movies and TV shows released since 2000, performs data analysis, and exports the results to CSV files.
Features

Scrapes movie and TV show data from JustWatch
Extracts information such as title, release year, genre, IMDb rating, and streaming services
Filters data based on release year and IMDb rating
Performs basic data analysis on the scraped data
Exports both raw and filtered data to CSV files

Requirements

Python 3.x
Required libraries:

BeautifulSoup4
requests
pandas
numpy
matplotlib
wordcloud



Installation

Clone this repository or download the script.
Install the required libraries:

Copypip install bs4 requests pandas numpy matplotlib wordcloud
Usage

Run the script:

Copypython web_scrapping_mid_assessment.py

The script will perform the following actions:

Scrape movie and TV show data from JustWatch
Filter the data based on specified criteria
Perform data analysis
Generate visualizations
Export the data to CSV files



Output
The script generates the following CSV files:

Just watch Movies Info.csv: Raw data for all scraped movies
Just watch TV Show Info.csv: Raw data for all scraped TV shows
Recent Good Movies Info.csv: Filtered data for movies released in the last 2 years with an IMDb rating of 7 or higher
Recent Good TV Show Info.csv: Filtered data for TV shows released in the last 2 years with an IMDb rating of 7 or higher

Data Analysis
The script performs the following analyses:

Calculates the average IMDb rating for movies and TV shows
Identifies the top 5 genres for movies and TV shows
Determines the most common streaming service for movies and TV shows

Visualizations
The script generates word clouds for:

Top 5 movie genres
Top 5 TV show genres
Top 5 streaming services for movies
Top 5 streaming services for TV shows

Notes

The script includes delays between requests to avoid overloading the server
Error handling is implemented to manage potential issues during scraping
The script uses headers to mimic browser requests for better reliability

Disclaimer
This web scraper is for educational purposes only. Make sure to comply with JustWatch's terms of service and robots.txt file when using this script. The developers are not responsible for any misuse of this tool.
