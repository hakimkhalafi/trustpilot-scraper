# trustpilot-scraper
Python scraping tool for trustpilot.com reviews.

# Usage
 1) Set up up and configure [scrape.ipynb](scrape.ipynb) to scrape the page you want the reviews from into CSV file
 2) Use the [clean.ipynb](clean.ipynb) module to convert and clean this CSV file to a format used by most text classification algorithms

# Sentiment analysis
After you've run scrape and clean, you can use [this example](https://github.com/scikit-learn/scikit-learn/blob/master/doc/tutorial/text_analytics/solutions/exercise_02_sentiment.py) from sci-kit learn to do text classification.
