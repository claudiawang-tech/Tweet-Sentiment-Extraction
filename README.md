# Tweet-Sentiment-Extraction
A NLP Project | Extract support phrases for sentiment labels

## Description
This is a code competition held by [Kaggle](https://www.kaggle.com/c/tweet-sentiment-extraction). The objective in this competition is to construct a model that look 
at the labeled sentiment for a given tweet and figure out what word or phrase best supports it.

I predicted the word or phrase from the tweet that exemplifies the provided sentiment. 
The word or phrase included all characters within that span (i.e. including commas, spaces, etc.). 
The format is as follows:
<id>,"<word or phrase that supports the sentiment>"

For example:
2,"very good"

## Datasets

**Files**
* train.csv - the training set
* test.csv - the test set
* sample_submission.csv - a sample submission file in the correct format

**Columns**
* textID - unique ID for each piece of text
* text - the text of the tweet
* sentiment - the general sentiment of the tweet
* selected_text - [train only] the text that supports the tweet's sentiment

## Evaluation
The metric in this competition is the word-level Jaccard score.

## Accomplishments
My team is the top 28% of the 2,227 teams.
