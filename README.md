This project is a recommender systems using item-based collaborative filtering. There are 2 types of recommender systers:
 i) User Based Recommender Systems
ii) Item Based Recommender Systems

Both requires a user-item matrix (users as rows and items in columns). Cold-start problem exist in both where the alternative is to recommend based on similar profile/demographic/background.

Item based recommender is superior because the former measures similarity across every row and comparing them, resulting in a) expensive computation and b) people's preference may change over time then current recommendation may not account for these shifts. In item based recommender, similarity is computed across items, making them to a degree less sensitive to small changes in preference in handful of individuals as the number of users is extensive. 

Data from https://www.kaggle.com/grouplens/movielens-20m-dataset

In this project, the items are movies.