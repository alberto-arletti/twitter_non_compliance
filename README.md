# Description of the data and file structure
The data was collected as part of a research aiming to investigate online support for covid 19 restrictions non-compliance. To do so, the tweet feed of Italian tweets regarding a mass non-compliance event in Italy (port protests of Trieste) was collected through the Twitter API, using an academic account, during 2021 as part of partial fulfilment of a Master Degree in Psychological Science. 

# Files and variables
File: processed_anon.csv
Description: 

# Variables
* author_id: Unique identifier for the author of the tweet.
* tweet_id: Unique identifier for each tweet.
* created_at: Timestamp indicating when the tweet was created (in ISO format).
* location: The geographic location of the user when the tweet was posted.
* username: The Twitter handle or username of the tweet author.
* type_1: Type of interaction related to the tweet, such as "replied_to".
* is_retweet: Boolean indicating whether the tweet is a retweet (True/False).
* mentions: Number of user mentions within the tweet.
* urls: Number of URLs included in the tweet.
* hashtags: Number of hashtags used in the tweet.
* retweet_count: Number of times the tweet was retweeted.
* reply_count: Number of replies the tweet received.
* like_count: Number of likes the tweet received.
* quote_count: Number of times the tweet was quoted.
* followers_count: Number of followers the user has.
* following_count: Number of accounts the user is following.
* tweet_count: Total number of tweets made by the user.
* fulltext: The full content of the tweet.
* joy: Emotion analysis score representing the level of joy in the tweet.
* anger: Emotion analysis score representing the level of anger in the tweet.
* fear: Emotion analysis score representing the level of fear in the tweet.
* sadness: Emotion analysis score representing the level of sadness in the tweet.
* best_result: Dominant emotion detected in the tweet (e.g., joy, fear, anger, sadness).
* support: Score indicating the level of support for the subject of the tweet.
* neutral or against: Score indicating whether the tweet is neutral or against the subject.
* Topic: Categorization of the tweet into predefined topics (e.g., protests, noise).
* Description: Summary of the tweet's content.
* Meta: Additional metadata related to the tweet's topic or context.

# Code/software
The data in .csv can be opened with one of the many free or premium software such as Excel, google sheet and the like.  
Python 3.0, with pandas, numpy, matplotlib for visualization and manipulation.\
For regression analysis, we suggest the use of Rstudio lme4 library. 

# Access information
Other publicly accessible locations of the data:
* None
Data was derived from the following sources:
* Twitter (in 2021)
