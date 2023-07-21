# News Fetcher Script

This script utilizes the News API to fetch and display top headlines from various news sources based on user input. The script accepts command-line arguments and provides two main functionalities:

1. Fetching top headlines by category:
   The script allows users to retrieve top headlines from the specified news category for the United Kingdom (country code "gb").

2. Fetching top headlines by query:
   Users can also search for top headlines containing a specific query term, again for the United Kingdom.

## Prerequisites

Before running the script, ensure you have the following:

1. Python installed on your machine.
2. The `requests` library, which you can install using `pip install requests`.

## Instructions

1. Save the script in a Python file, e.g., `news_fetcher.py`.
2. Make sure you have an API key from News API. If you don't have one, sign up for a free account at [https://newsapi.org](https://newsapi.org).
3. Replace `'071cd4ab1c084e9498a1fbd25335d237'` with your actual API key in the script.

## Usage

To run the script, use the following format:

python news_fetcher.py <category_or_query>

Replace `<category_or_query>` with either a news category (e.g., "business", "entertainment", "sports") or a specific query term (e.g., "Liz Truss", "technology").

## Examples

1. To fetch top headlines for the "business" category, run:

python news_fetcher.py business


2. To fetch top headlines containing the query term "Liz Truss", run:

python news_fetcher.py "Liz Truss"


3. To fetch top headlines for a specific query like "technology", you can modify the script's `get_artciles_by_query()` function call.

## Notes

- The script fetches and displays top headlines from various news sources in the United Kingdom (country code "gb").
- The News API has usage limits for free accounts, so keep that in mind when using the script regularly.

Enjoy exploring the latest news headlines with this simple Python script!
