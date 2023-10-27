# Python-Project-Submission--Salem
Movie Suggestion Bot

## Overview

This project presents a movie suggestion bot designed to recommend movies based on a genre inputted by the user. The bot employs web scraping techniques to gather movie data from IMDb, and then uses this data to suggest relevant movies according to user preferences.

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


## Dependencies
beautifulsoup4: Utilized for web scraping IMDb.
pandas: Used for data manipulation and reading from the .csv file.
requests: Facilitates making HTTP requests to IMDb.

## Screenshots
A series of screenshots showcasing the bot in action are included in the repository. These provide visual insights into the bot's functionality, error handling capabilities, and user interface.

## Future Improvements
Integration of user reviews and ratings for more tailored suggestions.
Expanding the bot's genre database for a wider variety of movie recommendations.
Implementing a GUI for enhanced user experience.
