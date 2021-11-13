# Movie Recommender

This project uses data from the ml-100k dataset to generate movie recommendations based on what similar users in the data set enjoyed. It was built using Apache SparkSQL and Datasets.


Link to data: https://grouplens.org/datasets/movielens/100k/

We used the cosine similarity metric to compute a similarity rating which is how we were able to generate recommendations. We set the threshold to 0.97 to be able to recommend a movie.

The Spark driver script takes in a movieID as an argument from the u.item dataset and outputs 10 movie recommendations based on that movie.
