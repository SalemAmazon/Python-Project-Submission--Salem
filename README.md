# Python-Project-Submission--Salem
Movie Suggestion Bot

## Overview

This project presents a movie suggestion bot designed to recommend a movie based on a genre inputted by the user. The bot employs web scraping techniques to gather movie data from IMDb, and then uses this data to suggest relevant movie according to user preferences.

## Features

- **Genre-Based Suggestions:** The bot takes a genre as input and provides a movie recommendation based on that genre.
- **Web Scraping:** The application uses web scraping libraries like `beautifulsoup4` to fetch movie data from IMDb.
- **Data Handling:** The scraped data is stored in a `.csv` file for persistence. Pandas library is integrated for efficient data retrieval and manipulation.
- **Error Handling:** Implemented robust error handling to ensure the bot runs smoothly even if unexpected inputs or issues arise.

## Getting Started

### Prerequisites

Ensure you have the required libraries installed by running:

```bash
pip install beautifulsoup4 pandas requests jupyter
