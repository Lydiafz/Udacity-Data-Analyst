# Udacity DataWrangling Project

## Introduction

This project is one of the Udacity Data Analyst Nanodegree projects. In this project, the dataset that I wrangled, analyzed, and visualized is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for students to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. In this report, I was trying to exploring this huge
dataset in different ways, and investigated the patterns and the relationship among people’s rating,
retweet, favorite, and prediction probability etc.

## Data Files used

### This dataset includes three separate datasets from different sources.
• Data1 is the “twitter_archieve-enhanced.csv” data, which was already provided.
• Data 2 is the “image-predictions.csv” data that downloaded from the url
  https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv 
• Data 3 is the retweet and favorite information from the twitter API, which was intinally saved as "tweet_json.txt"

## Project steps: all the following steps were conducted using jupyter notebook.

• Data Gathering: Using tweepy, json API and python functions to obtain the files mentioned above

• Data Assessing: Visually and programtically check the three data sets, identified the quality issues and tidiness isssues.

• Data Cleaning: Address all the assessed issues, and merge three dataset into one clean final dataframe for further 

  visualization and analyses
  
• Data Visualization: Condunct some preliminary analyses and visualization on the dataset and get some conclusions.

## Reports

• wrangle_report: The effort I made during the data wrangling.

• act_report: The preliminary results and visualizatin that made based on the final clean dataset.

