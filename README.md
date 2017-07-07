# Content-based recommender system using Movielens dataset

Notebook to illustrate basics of content-based recommendation. We build a recommender matrix of all users ratings (rows) vs movie titles (columns) and then use a correlation function to identify similar films to one selected film.

Movielens user data set (u.data) obtained from http://files.grouplens.org/datasets/movielens/ml-100k.zip.

We are using the 100,000 user ratings database. The above zip file contains other files including the README with more info about the data.

From the README we can see the following:
- The u.data file contains the full data set of 100,000 ratings by 943 users on 1682 items.
- Each user has rated at least 20 movies.
- Users and items are numbered consecutively from 1.
- The data is randomly ordered.
- This is a tab separated list of user id | item id | rating | timestamp.
- The time stamps are unix seconds since 1/1/1970 UTC.

The Movie_Id_Titles contains movie titles
- There are 1683 rows (movie titles).
- Row 1 contains headers 'item_id', 'title'.
- Rows 2 to 1683 contain the titles.
