# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Reddit Web APIs & Classification

### Background

Reddit is a massive collection of forums where people share news and content or comment on other people’s posts. Reddit is broken up into more than a million communities known as “subreddits” and each of which covers a different topic.


### Problem Statement

There are posts related to Pytorch and Tensorflow which could be wrongly in subreddits having similar content, and might require the moderators of the subreddits to clean it up to ensure content relevancy for viewers.

In this project, I aim to develop classifier models via machine learning techniques and identify if a Naive Bayes classifer or another classifier model would be suitable in classifying if a reddit post belongs to the either Pytorch or Tensorflow subreddits.

### Executive Summary

The growing AI industry and the availability of open-sourced frameworks online such as the Tensorflow and Pytorch, the top 2 common frameworks used for implementing various neural network architecture by AI researchers, enthusiasts and application engineers has resulted in lots of questions and answers, especially in Reddit. 

As such there might be posts on Reddit site related to the two frameworks that could be wrongly posted in wrong subreddits. In view of the increasing amount of posts, it would be beneficial for subreddit stakeholders to have a classifier that helps to classify related posts/comments which are posted incorrectly in various subreddits as part of their cleanup process.

In this project, more than 900 reddit posts have been scraped from both Pytorch and Tensorflow subreddits respectively via Reddit's API, for the purpose of training classifier models which could potentially recommend Reddit moderators if a specific post should be moved to correct subreddit.
