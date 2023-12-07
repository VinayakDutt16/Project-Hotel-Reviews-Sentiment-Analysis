# Project-Hotel-Reviews-Sentiment-Analysis

Data Loading:

The project starts by importing necessary libraries, downloading the VADER lexicon for sentiment analysis, and loading a CSV file named "hotel.csv" into a Pandas DataFrame (df).
Data Exploration:

Initial exploration of the dataset is performed using df.head() to display the first few rows of the DataFrame.
Data Visualization:

The project utilizes Seaborn and Matplotlib to create a pie chart visualizing the distribution of hotel ratings. Ratings are extracted from the "Rating" column of the DataFrame.
Sentiment Analysis:

The Natural Language Toolkit (nltk) is used for sentiment analysis with the VADER sentiment intensity analyzer. Sentiment scores (positive, negative, neutral) are calculated for each review in the "Review" column of the DataFrame.
The positive, negative, and neutral scores are stored in new columns ("Positive," "Negative," "Neutral") in the DataFrame.
Summary Statistics:

The project calculates the total sum of positive, negative, and neutral sentiment scores for all reviews.
Sentiment Classification:

A custom function (sentiment_score) is defined to classify the overall sentiment based on the cumulative positive, negative, and neutral scores.
Results Display:

The sentiment classification result (Positive, Negative, or Neutral) is printed based on the custom function.
The total positive, negative, and neutral scores are also printed.
Conclusion:

The project provides a basic analysis of hotel reviews, visualizing ratings distribution and sentiment analysis results.
The sentiment analysis classifies the overall sentiment of the reviews into Positive, Negative, or Neutral based on the cumulative sentiment scores.
