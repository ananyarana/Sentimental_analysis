# Sentimental_analysis
There are two datasets, train.csv and test.csv which contain tweets of different usernames. I have taken these datasets from online sources and I have not uploaded these datasets being too large. 
I have preprocessed the data by removing unwanted information from the dataset after combining both train.csv and test.csv.
The vaderSentiment library is used from which SentimentIntensityAnalyzer function is imported. This function calculates the sentiment score of the string(here tweets). Therefore, we can classsify the score into Positive, Negative and Neutral.
