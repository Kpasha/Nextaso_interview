GENERAL INFORMATION
It is a Natural Language Processing Problem 
where Sentiment Analysis is done by Classifying the Positive tweets from negative tweets by 
machine learning models for classification, text mining, 
text analysis, data analysis and data visualization

Title of Dataset: Sentiments Analysis for review text does not match rating
The dataset already contains the classification, which can be positive or negative, and 
the task at hand is to identify which words appear more frequently on reviews from each of the classes.



Requirements
There are some general library requirements for the project and some which are specific to individual methods. 
The general requirements are as follows.

numpy
scikit-learn
scipy
nltk
The library requirements specific to some methods are:
Note: It is recommended to use Anaconda distribution of Python.

METHODOLOGICAL INFORMATION

In the multivariate event model, features are independent binary variables describing inputs.

### Data collection
Description of methods used for collection/generation of data: 

The preprocessing of the text data is an essential step as it makes the raw text ready for mining, 
i.e., it becomes easier to extract information from the text and apply machine learning algorithms to it. 
If we skip this step then there is a higher chance that you are working with noisy and inconsistent data. 
The objective of this step is to clean noise those are less relevant to find the sentiment of tweets such as punctuation, 
special characters, numbers, and terms which don’t carry much weightage in context to the text.



End Notes
In this article, we learned how to approach a sentiment analysis problem. 
We started with preprocessing and exploration of data. 
Then we extracted features from the cleaned text using Bag-of-Words and TF-IDF. Finally, 
we were able to build a couple of models using both the feature sets to classify the tweets.