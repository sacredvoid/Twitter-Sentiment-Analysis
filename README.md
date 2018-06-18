# Twitter-Sentiment-Analysis

This is an implementation of Opinion Mining, ie. fetching tweets from your Twitter Account using the official Twitter API Tweepy.<br />
It uses TextBlob library that helps us find the polarity of a sentence by tokenizing it and applying Natural Language Techniques. <br />

## Important packages to run this file: 
Tweepy (http://docs.tweepy.org/en/v3.4.0/install.html), TextBlob(http://textblob.readthedocs.io/en/dev/install.html) and re (https://pypi.org/project/re2/) <br />

## Steps to follow before running the code (SentimentAnalysis.py): <br />
1. https://apps.twitter.com/ Go to this link and create a new app. (You must be logged into twitter and should have your mobile number connected to the twitter account.)<br />
2. Give a name, Description and a URL (or a placeholder, preferably https://my.example.placeholder)
3. Click 'Create' after accepting the terms and conditions.
4. From there you can go to the 'Keys and Access Tokens' Tab and paste the respective access codes into the code file 'SentimentAnalysis.py' where you find a string like 'XXXXXX'.<br />
5. Run the code and you'll see the percentages of postive and negative tweets and the top 5 positive and negative tweets itself. <br />
6. You can even change the topic of the tweets to be fetched by changing it in the 'tweets' variable within the main() function. Current topic is 'World Cup 2018'.<br />
