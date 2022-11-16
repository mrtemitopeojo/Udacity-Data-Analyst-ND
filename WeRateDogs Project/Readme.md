# Wrangling and Analyzing a Twitter Page that Rates Dogs

This project explores a Twitter user called "WeRateDogs" to get a better sense into the types of dogs rated and answer questions on what the followers of the page find interest in. 

## Dataset

The data used for this project is a gathering of 3 different datasets:
- An existing downloaded archived data supplied by Udacity
- Using the Requests library to download tweet image prediction (needed to get image predictions of each dog rated)
- Using Tweepy to query additional data via Twitter API
- A master dataframe having the combination of all 3 above after wrangling, can be found in project, file name - "twitter_archive_master" (about 1974 rows, 26 columns)

## Code

I splitted the code various subsections to make the notebook easy to read and understand. The sections were:

- Data Gathering
  - Archived twitter data
  - Image prediction data
  - Querying directly from Twitter using API
- Data Assessing
- Data Cleaning
- Data Storage
- Data Analysis & Visualization

## Goal/Questions Answered

The goal of the project was to answer questions based on the data available, some of the questions asked and answered in the file include:

- What stage of dog was more prominent
- Trend of followers of WeRateDogs twitter account across the period the data was collected
- Dog names that are most prominent in WeRateDogs twitter account
- Heat map showing the relationships between retweets, favourites, followers

You would want to check out the files "Act_report"(gives a summary of insights gotten in the project and questions asked) and "Wrangle_report"(summarizes the whole project, and steps taken at each point in time to arrive at the conclusion)

## Dependencies/Libraries

Libraries used in this project include:

- pandas - for reading and exploring the dataset 
- numpy - allows for easy mathematical manipulations of dataset
- matplotlib - python plotting library to beautify visualizations
- seaborn - plotting library majorly for exploring visualizations as it does not have as much customizable features as matplotlib.
- requests - library used to access API's
- os - library that helps accessing file and folder paths in local system easy
- re - regular expressions library that helps with advanced string manipulations
- bs4 - A library that helps access to data on websites easy
- json - library used to help read javascript oriented notation
- tweepy - twitters access library
- io - useful for performing file I/O operations
- PIL - library used to improve access to image files  
- %matplotlib inline - allows visualizations to be visible in notebook

