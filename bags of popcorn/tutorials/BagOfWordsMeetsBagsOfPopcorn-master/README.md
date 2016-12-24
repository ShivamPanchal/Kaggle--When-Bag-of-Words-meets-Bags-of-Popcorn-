# Kaggle Sentiment analysis -- Bag of Words Meets Bags of Popcorn¶
[notebook view](http://nbviewer.jupyter.org/github/xchaoo/BagOfWordsMeetsBagsOfPopcorn/blob/master/BagOfWordsMeetsBagsOfPopcorn.ipynb)
## Background
情感分析是机器学习中一个具有挑战性的课题。人们在表达语言时，具有很多技巧性，同一语句在不同语境下往往具有不同语意，而这些可能会导致人或者电脑的误解，本题给出了IMDB电影评论中部分有标注的训练数据，目的是预测测试集中评论积极或者消极。
## Data Set
The labeled data set consists of 50,000 IMDB movie reviews, specially selected for sentiment analysis. The sentiment of reviews is binary, meaning the IMDB rating < 5 results in a sentiment score of 0, and rating >=7 have a sentiment score of 1. No individual movie has more than 30 reviews. The 25,000 review labeled training set does not include any of the same movies as the 25,000 review test set. In addition, there are another 50,000 IMDB reviews provided without any rating labels.
## Data fields
* id - Unique ID of each review
* sentiment - Sentiment of the review; 1 for positive reviews and 0 for negative reviews
* review - Text of the review