# trustpilot-scraper
Python scraping tool for trustpilot.com reviews

# Usage
First set up and configure [scrape.ipynb](scrape.ipynb) to scrape the page you want the reviews from into CSV file
Then you can use the [clean.ipynb](clean.ipynb) module to convert and clean this CSV file to a format used by most text classification algorithms

# Sentiment analysis
After you've run scrape and clean, you could use this for example with sci-kit learn text classification: 
https://github.com/scikit-learn/scikit-learn/blob/master/doc/tutorial/text_analytics/solutions/exercise_02_sentiment.py
