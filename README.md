# Yelp Project

### Project's Goal
In this project we will be using natural language processing in an attempt to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews.

### Details about the data set
We will use the [Yelp Review Data Set from Kaggle](https://www.kaggle.com/c/yelp-recsys-2013).

Each observation in this dataset is a review of a particular business by a particular user.

The "stars" column is the number of stars (1 through 5) assigned by the reviewer to the business. (Higher stars is better.) In other words, it is the rating of the business by the person who wrote the review.

The "cool" column is the number of "cool" votes this review received from other Yelp users.

All reviews start with 0 "cool" votes, and there is no limit to how many "cool" votes a review can receive. In other words, it is a rating of the review itself, not a rating of the business.

The "useful" and "funny" columns are similar to the "cool" column.

### Exploring the data

Through the following histograms, we can notice that the distribution of the text lengths seems to be the same for all the number of stars. However, the actual amount of text reviews skewed a lot higher towards 4 or 5 stars.




