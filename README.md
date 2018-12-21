# Unsupervise Learning--Movielens-Recommendation-System

### About Dataset
This dataset describes 5-star rating and free-text tagging activity from [MovieLens](http://movielens.org), 
a movie recommendation service. It contains 100004 ratings and 1296 tag applications across 9125 movies. 
These data were created by 671 users between January 09, 1995 and October 16, 2016. 
This dataset was generated on October 17, 2016.
Users were selected at random for inclusion. All selected users had rated at least 20 movies. 
No demographic information is included. Each user is represented by an id, and no other information is provided.
The data are contained in the files `links.csv`, `movies.csv`, `ratings.csv` and `tags.csv`. \
This data sets are publicly available for download at <http://grouplens.org/datasets/>. More details please see the readme about dataset

### About Project
In this project, I combined movie dataset with user dataset then create pivot table to get a new rating matrix.
After filling the missing values, and make cross validation, I use cosine similary , classic SVD and funk SVD algorithm to create
recommendation system to make predictions, and then compare the result of each algorithm. Finally, funk SVD is a most efficient and 
accurate way to do recommendation.
