# Unit 12 - Tales from the Crypto

![Bitcoin and Ethereum](https://www.bitcoinmarketjournal.com/wp-content/uploads/2019/04/bitcoin-ethereum.jpg)

## Background 

The purpose of this assignment is to apply Natural Language Processing techniques to analyze the setiment of Bitcoin and Ethereum using recent news articles pulled from the newsapi. This notebook runs through Sentiment Analysis, NLP and Named Enity Recognition. 



## Sentiment Analysis 

Here we use the newapi to load in current news aricles relating to Bitcoin and Ethereum. After cleaning up the data, implemting polarity scores and formualting seperate DataFrames for each coin, to understand the sentiment we when then run a basic .describe() method on the scores.

### Questions:

Q: Which coin had the highest mean positive score?

A: Bitcoin had the highest mean positive score with a score of 0.055740

Q: Which coin had the highest compound score?

A: Ethereum had the highest compound score with a score of 0.827100

Q. Which coin had the highest positive score?

A: Bitcoin had the highest positive score with a score of 0.269000


## Natural Language Processing

Here we use NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins.


## Named Entity Recognition 

Lastly we utilize the SpaCy package to build a named entity recognition model for both Ethereum and Bitcoin
