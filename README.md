# GoodReads-Reviews

## Overview

This project explores and analyzes Goodreads book review data to identify patterns and trends in reader ratings and review sentiment. The analysis combines data cleaning, exploratory data analysis (EDA), natural language processing (NLP), and sentiment analysis to better understand how readers respond to books.

This project serves as my introduction to NLTK and various sentiment analysis techniques, allowing me to explore and apply different NLP and sentiment analysis functions to real-world review data.

## Dataset

The datasets used in this analysis came from [Goodreads Book Graph Datasets](https://cseweb.ucsd.edu/~jmcauley/datasets/goodreads.html) under the romance genre category. There are two datasets: a book dataset and a reviews dataset.

Important columns include:
- Book Title
- Book ID
- Review Text
- Review ID
- Rating

## Workflow

### Data Cleaning

The datasets were cleaned by retaining only English-language reviews, excluding reviews containing links (identified by "http"), and removing blank reviews.

### Exploratory Data Analysis

Before conducting further analysis, I created a plot to visualize the distribution of ratings from 0 to 5. The graph shows an increasing distribution, with 0- and 1-star ratings having the lowest counts, while 5-star ratings have the highest count.

## Sentiment Analysis

Two sentiment analysis approaches were explored:

### VADER

VADER was used to calculate sentiment scores for reviews and classify them into positive, neutral, or negative sentiment.

### RoBERTa

A pretrained RoBERTa-based sentiment model was used to provide a second sentiment classification approach.

The results from both approaches were compared to examine differences in sentiment classification.