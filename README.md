# JustWatch Web Scraper
## Overview
I developed a web scraper to extract and analyze movie and TV show information from JustWatch. This project focuses on collecting data for movies and TV shows released since 2000. The scraper performs data analysis and exports the results to CSV files for easy access and further analysis.

## Features
### Data Extraction:
I built the scraper to extract essential information such as the title, release year, genre, IMDb rating, and available streaming services for movies and TV shows.

### Filtering: 
I implemented filters to select titles based on their release year and IMDb rating, allowing for more focused data analysis.

### Data Analysis: 
Using the collected data, I performed basic analysis to derive insights like average IMDb ratings, popular genres, and top streaming services.

### Visualization: 
I generated visualizations such as word clouds to represent the top genres and streaming services.

### CSV Export: 
I exported both raw and filtered data into CSV files to facilitate further use and sharing.

## Requirements
Python 3.x
## Required Libraries

beautifulsoup4

requests

pandas

numpy

matplotlib

wordcloud

I ensured that these libraries are necessary for scraping, data analysis, and visualization tasks. You can install them using:

*pip install beautifulsoup4 requests pandas numpy matplotlib wordcloud*

## Installation

Clone this repository or download the script.

Install the required libraries as outlined above.

## Usage

### Run the script:

*python web_scrapping_mid_assessment.py*

### The script performs the following actions:

Scrapes movie and TV show data from JustWatch.

Filters the data based on the specified criteria (e.g., release year, IMDb rating).

Conducts data analysis and generates visualizations.

Exports the collected and processed data to CSV files.

## Output

### Generated CSV Files

JustWatch_Movies_Info.csv: Contains the raw data for all scraped movies.

JustWatch_TV_Show_Info.csv: Contains the raw data for all scraped TV shows.

Recent_Good_Movies_Info.csv: Lists movies released in the last 2 years with an IMDb rating of 7 or higher.

Recent_Good_TV_Show_Info.csv: Lists TV shows released in the last 2 years with an IMDb rating of 7 or higher.

## Data Analysis

### I performed the following analyses on the scraped data:

Average IMDb Rating: Calculated the average rating for both movies and TV shows to gauge overall quality.

Top Genres: Identified the top 5 genres for movies and TV shows to understand current trends.

Popular Streaming Services: Determined the most common streaming services to see where most content is available.

## Visualizations

I created visual representations to enhance the analysis:

### Word Clouds:

Top 5 movie genres

Top 5 TV show genres

Top 5 streaming services for movies

Top 5 streaming services for TV shows

## Notes
I included delays between requests in the scraper to avoid overloading the server and to mimic natural browsing behavior.

I implemented error handling to manage potential issues during the scraping process, ensuring robustness.

The script uses headers to mimic browser requests, which enhances reliability and reduces the chances of being blocked by the server.
