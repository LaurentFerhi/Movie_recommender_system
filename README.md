# Movie_recommender_system

This notebook provides a item-based recommender system based on the movie lens dataset:
https://www.kaggle.com/prajitdatta/movielens-100k-dataset

It uses a pairwise distance metric to compute similarities between items. The idea is to provide the user a list of recommended movies based on the movies that the user already rated.

For instance, the user rated:
- Star Wars             - rated: 5
- Return of the Jedi    - rated: 5
- Net, The              - rated: 2

The recommender system will return:
- Raiders of the Lost Ark 
- Empire Strikes Back, The 
- Toy Story 
- Indiana Jones and the Last Crusade 
- Independence Day (ID4) 
...
