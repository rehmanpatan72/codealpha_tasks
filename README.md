# Books Sentiment Analysis

A Data Analytics Internship project completed using Python and Google Colab for web scraping, data cleaning, exploratory data analysis (EDA), and sentiment analysis of book descriptions.

## Project Overview

This project analyzes book data collected from [Books to Scrape](https://books.toscrape.com/). It explores book prices, ratings, categories, stock availability, and sentiment polarity derived from book descriptions.

## Objectives

- Scrape book data from 50 catalogue pages.
- Clean book prices, ratings, and stock quantities.
- Perform Exploratory Data Analysis (EDA).
- Visualize rating and price distributions.
- Analyze book-description sentiment using TextBlob.
- Examine the correlation between book ratings and description sentiment polarity.

## Tools and Technologies

- Python
- Google Colab
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- Seaborn
- TextBlob

## Methodology

1. Scraped book information from 50 catalogue pages.
2. Collected 1,000 book records.
3. Cleaned price and rating values and extracted stock quantities.
4. Performed EDA using statistical summaries and visualizations.
5. Calculated sentiment polarity from book descriptions using TextBlob.
6. Examined the relationship between ratings and sentiment polarity using correlation analysis and a scatter plot.

## Key Results

- **Total books collected:** 1,000
- **Average book price:** £35.07
- **Minimum book price:** £10.00
- **Maximum book price:** £59.99
- **Rating–sentiment correlation:** 0.067

The correlation indicates a very weak positive linear relationship between book ratings and description sentiment polarity.

## Visualizations

The project includes:

- Book rating distribution
- Book price distribution
- Average price by rating
- Rating versus description sentiment polarity scatter plot

## Important Limitation

Sentiment analysis was performed on book descriptions, not customer reviews. Therefore, the sentiment scores do not directly measure customer opinions or satisfaction.

## Project Files

- `CodeAlpha_BooksSentimentAnalysis.ipynb` — Notebook containing the Python code and analysis.
- `books_sentiment_analysis.csv` — Cleaned dataset with sentiment results.

## How to Run

1. Download or clone this repository.
2. Open `CodeAlpha_BooksSentimentAnalysis.ipynb` in Google Colab.
3. Run the notebook cells in order.
4. Install the required Python libraries if they are not already available.

## Author

**Data Analytics Internship Project — CodeAlpha**

Name: Muhammad Rehman