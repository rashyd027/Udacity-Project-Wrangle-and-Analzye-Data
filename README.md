# Udacity-Project-Wrangle-and-Analzye-Data
# by Lawal Rasheed

# Objectives

This is a repository for Udacity Data Analyst Project 2 (Data Wrangling). The dataset used in the project is also included in this repository. The aim is to broaden my data gathering skills as well as to produce insights from the analysis.

# Installation

The libraries/packages used on this project include:

* Pandas
* Numpy
* Matplotlib
* Tweepy
* Requests
* os
* json
* re

# Introduction

Data gathering was done using three methods:

1. Using pandas read_csv
2. Using Requests library to gather image predictions data
3. Tweepy library to gather additional data via Twitter API.

# Project Methodology

The main steps for this project can be summarized as follows:

* Data Wrangling;
  * Data Gathering
  * Data Assessment
  * Data Cleaning
* Analysis/Visualization

# Results

Based on the data and analysis carried out;

* @WeRateDogs audience likes Doggo and Puppo dogs much more than any. If @WerateDogs is trying to garner engagements on his tweets, he should post more on doggo and puppo dogs to garner more likes.

* Tweeting from an Iphone gathers more likes, but it is worthy to note that there are other factors that could be at play such as contents of the tweet, the dog_stage as well.

* There is a positive relationship/correlation between Retweets and Likes. Also the Pearson's coefficient is 0.86 which is close to 1 (positive correlation). As any tweet, Tweeted by WeRateDogs gets retweeted, there is a likely increase in number of Likes.

# Limitations

1. I was unable to retrieve the tweet status of about 29 tweets while querying twitter.
2. Based on cleaning tweets that did not have a dog name, a particular source 'Vine - Make a Scene' was eliminated, hence the analysis is representative of only a short sample.
