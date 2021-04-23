# README 

Project for course at Wageningen University 

This project contains the work done for the Wageningen University course _Datascience for Smart Environments_.

The goal of this project is to do an exploratory data analysis on tweet sentiments with the aim of answering the following questions:

- To what extend do the sentiments in four major Dutch cities differ?
- To what extend do the sentiments in four major Dutch cities differ over time?
- To what extend do the sentiments of tweets from four major cities reflect corona-related events? 

It contains three main notebooks:

1. Get_Historic_Tweets.ipynb : Harvesting of tweets through twitters REST API
2. Sentiment_Analysis.ipynb : Cleaning the harvested tweets and running a sentiment analysis on them
3. Visualisations_Analysis.ipynb : Visualizing and analysing the tweet sentiments  

Also included are two csv files:
- Tweets
- Filtered tweets

The Tweets file contains all tweets harvested in 1. Get_Historic_Tweets.ipynb, and acts as input for 2. Sentiment_Analysis.ipynb. 
The Filtered tweets contains the tweets that have been processed in 2. Sentiment_Analysis.ipynb. It acts as input for 3. Twitter_Project_Visualizations.ipynb. 
 
Each notebook contains a short introduction and a discussion on the decisions made and problems encoutered in the process of writing the code.

This project contains additional work on Live Stream API's, that is interesting on itself but not connected to the main project. 
Info on this is found in the Live_API.ipynb
