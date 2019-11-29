# RedditLoseitAnalysis
Analysis on /r/loseit for research on emotional eating

This repository is for study on online emotional eating behavior, based on posts and comments of /r/loseit.

For this study, 185,950 posts and 3,528,107 comments were collected and investigated by medical expert and data scientists.

Posts were first classified into emotional and non-emotional eating related posts, and then clustered into certain number of topics using LDA. Comments, or feedback on emotional eating related posts were also divided into topics with LDA. 

loseit_esre_classification_final.ipynb : For preprocessing and classifying posts using various machine learning models
cross_validation.ipynb : Cross validation of classification result and drawing roc curve
LDA_post.ipynb : LDA topic modeling for posts
LDA_comment.ipynb : LDA topic modeling for comments 


Certain machine learning and topic modeling methods were used for the study. Source codes are uploaded in this repository.

** thanks for crawling and providing data for the study: https://www.Reddit.com/r/bigquery/comments/3cej2b/
