# Twitter-Analysis

1.	tweets_oneyear.csv
This file collects information about 195,875 tweets created during 2021/10/15 and 2022/10/14. Columns include tweet ids, time being created, Twitter user ids, tweet content, number of times being retweeted, number of replies, number of likes, and number of times being quoted.

2.	users_oneyear.csv
This file collects information about 131,495 Twitter users created during 2006/7/13 and 2022/10/14. Columns include user ids, usernames, screen names, account descriptions, time being created, account verification status, number of followers, number of followings, number of tweets posted, number of joined public lists, and tweets SRH.

3.	tweets_train_complete.csv
This curated dataset contains 3,000 tweets which are randomly selected from the merged data frames of “tweets_oneyear.csv” and “users_oneyear.csv”. As a group of six, we manually labeled these 3,000 tweets, and the additional labels include user types, if the tweet is period trackers relevant, if the tweet mentions period tracker data privacy, and tweet sentiment.

4.	Data, Analytics, & Visualization.jpynb
This file contains all codes of this project and answers the individual research question: Change in proportion of tweets concerning period tracker data privacy over time. It has three sections: Data collection, data analysis, and visualization. It lists detailed steps of data importing, data trimming, user and tweet classifications with Naïve Bayes and Logistic Regression, and time series visualizations.

5. tweets_unique.csv
This dataset contains 26,093 tweets whose user types and tweet types are fully labeled by Naive Bayes and Logistic Regression models. It only contains individual posted and period tracker related tweets, and each of the 26,093 unique users is preserved with one tweet only, which is randomly selected from all tweets each user has posted.
