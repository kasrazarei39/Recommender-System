This repository is about the Bonus assignment of the cloud computing course.

> Instructor: [Dr. S. A. Javadi](https://scholar.google.com/citations?user=Va7RTUsAAAAJ&hl=en)


# Hadoop-Spark

One of the features of collaborative filtering is the selection of products based on the user's user, which we use to build recommender systems. The dataset used in this section is in two files: game.csv and ratings.csv. In the first file, the details of the games, and in the second file, the scores of the users are given with the details of the game ID, user ID and score.
By using the collabrative filter and based on the user-user method, a recommendation system will be developed, which will suggest the number of 5 games with the most similarity among the games that are not rated. 
We use both:
- ALS model for creating a model [file](https://github.com/kasrazarei39/Recommender-System/tree/main/RecommenderSystem/ALS)
-  The cosine similarity to solve this problem. [file](https://github.com/kasrazarei39/Recommender-System/tree/main/RecommenderSystem/Cosine%20Similarity) 

Then, in the output, we bring the name of the games along with their similarity score (in descending order of similarity score.)
