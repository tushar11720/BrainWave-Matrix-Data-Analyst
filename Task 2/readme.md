# Social Media Sentiment Analysis using Jupyter Notebook

## Overview
This project focuses on analyzing the sentiment of social media posts and comments using Python and Jupyter Notebook. The analysis is performed on data collected from Reddit, utilizing Natural Language Processing (NLP) techniques to determine the sentiment polarity of the text.

## Features
- **Data Collection:** Collects posts and comments from a specified subreddit using the Reddit API.
- **Sentiment Analysis:** Uses TextBlob to analyze the sentiment of posts and comments, categorizing them as Positive, Negative, or Neutral.
- **Visualization:** Provides visualizations of sentiment distribution and trends over time using Matplotlib.
- **Word Frequency Analysis:** Generates word clouds to visualize the frequency of words in posts and comments.

## Setup Instructions
1. **Prerequisites:** Ensure you have Python and Jupyter Notebook installed. You will also need to install the required libraries:
   ```bash
   pip install praw textblob pandas matplotlib wordcloud nltk
2. **Reddit API Credentials:** Set up your Reddit API credentials by creating an application on the Reddit website and obtaining the client_id, client_secret, and user_agent.
3. **Run the Notebook:** Open the provided Jupyter Notebook file and execute the cells step by step.
