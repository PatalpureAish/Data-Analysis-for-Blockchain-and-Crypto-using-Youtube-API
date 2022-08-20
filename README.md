
# Data-Analysis-for-Blockchain-and-Crypto-using-Youtube-API


Use youtube API to obtain data for videos on Blockchain and cryptos. Used Coin Bureau to understand the the trends in data with respect to blockchain and its role in bussiness.


## API Reference

#### Used Youtube API
Youtube API. Avaiable at https://developers.google.com/youtube/v3
## Documentation

Aim: 
a.Use Youtube API and how to obtain video data.
b.Analyzing video data and verify different market trends, by the video comments, likes and tag.
c.Explore the trending topics using NLP techniques

Steps of the project:
a.Obtain video meta data via Youtube API for the videos on blockchain
b.Prepocess data and engineer additional features for analysis
c.Exploratory data analysis
d.Conclusions

Data selection:I created my own dataset using the Google Youtube Data API version 3.0. 
Data limitations: I tried using Blockchain at Berkeley videos , however due to limited number of videos
the data set was not enough for analysis

Preprocessing & Feature engineering: To be able to make use of the data for analysis, we need to perform a 
few pre-processing steps. Firstly, I reformated some columns, especially the date and time columns such as "pushlishedAt" and "tags". In addition, I also think it is necessary to enrich the data with some new features that might be useful for understanding the videos' characteristics.
Check for empty values

Enriching data:calculate number of tags for each video, calculate title character length

Exploratory analysis:
a.Views distribution per channel:Used Seaborn Violin plot
b.Does the number of likes and comments matter for a video to get more views: Used Scatter plot
c.Does the video duration matter for views and interaction (likes/ comments):Used histogram to plot data
d.Wordcloud for words in title: Using NLP analyse terms frequently occuring

Conclusions and future research ideas:
a.The more likes and comments a video has, the more views the video gets, high popularity for cryptos translating into 
use cases for blockchain development.
b.Most-viewed videos tend to have average title length of 30-70 characters. Too short or too long titles seem to harm viewership
c.More viewership for crypto investments
d. Popularity of blockachain in e-commerce.

Project limitation:The number of videos is quite small, more data needed for a through blockchain analysis

Ideas for future research:
a. Do sentiment analysis on the comments and find out which videos get more positive comments and which videos get less positive comments
b.Do market research by analyzing questions in the comment threads and identifying common questions/ market gaps which could potentially filled

