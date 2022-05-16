# Music-Recommender-system using k-means clustering

The idea is to create a recommender system for music lovers which clubs the songs with similar genre and provide recommendations according to the user’s choice.
songs with similar genres have similar characteristics like similar energy, acoustics, valence, danceability, etc. So given a dataset with these features for various songs clustering songs using kmeans.
To find the optimal number of clusters, used various techniques such as Elbow method and Davies Bouldin Score and plot the scores for number of clusters ranging between 2 to 14 and according to our DB index, choose the optimal n_cluster with minimum DB score.
