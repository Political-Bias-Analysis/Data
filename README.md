# Data

The data repository includes all the clean data we used for our project. The repository contains four different sets of data. 

# Article_sentiments
The article_sentiments data is the data we used to run sentiment analysis on articles. The data is grouped by the four biased terms, which are abortion, immigration, race, and socioeconomic. Under each bias folder, we grouped the articles by media source as well as years. 

# Articles
The article data is obtained through scrapping. On the official media. website, we search through the key words and relate them to election and then obtain all the related article links. After the links were obtained, we then write another script the scraped the article contents and stored them into JSON files. The JSON files then serve as our backup in case the database tables are corrupted. 

# Election_results
The election results data contains two different sets of data. The first set of data is the election result data with Presidential, Senates, and House elections break down by years. The second set of data is the voter registration information. Through the combination of the two data sets, we are able to obtain the response variable of our Linear Regression model, which is the normalized vote count. 

# Twitter_sentiments
The Twitter sentiment data is the result after running the VADER sentiment analysis. The data contains the tweets, the associated biased term, the year, and the corresponding sentiment score for the tweet. 
