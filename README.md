# Python-Sentiment-Analysis
This is a python based project, in which we analyse Tweets on the basis of positive and negative tweets. 
We analyse the data in the form of Scatter plot of Net Score Vs Number of Retweets.

We have provided some synthetic (fake, semi-randomly generated) twitter data in a csv file named project_twitter_data.csv which has the text of a tweet, the number of retweets of that tweet, and the number of replies to that tweet. We have also words that express positive sentiment and negative sentiment, in the files positive_words.txt and negative_words.txt.

Functions used in this project are:-

1. def strip_punctuation(strWord):Which takes one parameter, a string which represents a word, and removes characters considered punctuation from everywhere in the word.

2. def get_pos(strSentences):Which takes one parameter, a string which represents a one or more sentences, and calculates how many words in the string are considered positive words. Use the list, positive_words to determine what words will count as positive. The function should return a positive integer - how many occurances there are of positive words in the text.

3. def get_neg(strSentences):Which takes one parameter, a string which represents a one or more sentences, and calculates how many words in the string are considered negative words. Use the list, negative_words to determine what words will count as negative. The function should return a positive integer - how many occurances there are of negative words in the text.

4. def writeInDataFile(resultingDataFile)Wwhich takes one parameter, a string which represents all data in project_twitter_data.csv, and write a csv file called resulting_data.csv, which contains the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score (how positive or negative the text is overall) for each tweet. The file have its headers in that order.
