# Google Play Reviews Scraper and Sentiment Analysis for Vidio Dot Com

This repository contains a project that scrapes user reviews from the **Vidio Dot Com** app on the Google Play Store using the [`google-play-scraper`](https://pypi.org/project/google-play-scraper/) library. The scraped reviews are exported to an **Excel** file, and sentiment analysis is performed on the reviews using Python, providing insights into user feedback, satisfaction levels, and overall sentiment toward the app.

## Project Overview

- **Scraping Reviews**: Using the `google-play-scraper` library, reviews from the Vidio Dot Com app are collected and stored in an Excel file.
- **Sentiment Analysis**: The reviews are analyzed to determine the sentiment (positive, negative, or neutral) using natural language processing techniques with Python libraries.
- **Visualizations**: Charts and graphs are generated to illustrate the distribution of sentiments and other key metrics related to the reviews.

## Features

- **Automated review collection**: Fetch reviews from Google Play for the Vidio Dot Com app.
- **Sentiment classification**: Classify reviews as positive, negative, or neutral.
- **Export to Excel**: Save the scraped reviews in Excel format for easy access and further analysis.
- **Data visualization**: Use Python libraries such as `matplotlib` and `seaborn` to visualize the sentiment analysis results.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- The following Python libraries:

```bash
google_play_scraper==1.2.7
imbalanced_learn==0.10.1
matplotlib==3.7.1
nltk==3.8.1
pandas==2.0.3
plotly==5.15.0
protobuf==3.20.3
Sastrawi==1.0.1
scikit_learn==1.2.2
seaborn==0.13.2
wordcloud==1.9.3
