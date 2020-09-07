## Building a simple but reasonable movie recommender system

This movie recommender is based on correlation between the movies.


### The recommender works as follows:
    
    1) Choose 5 different and random movies which the user rated at least 4.5 out of 5 stars
    2) Get the highest correlations from each of those movies and merge them together in an own list
    3) Filter data to remove all movies which has lower correlation than 0.5
    4) Create a list of movie recommendation and filter out movies that the user already had seen
    5) Draw a sample out of the list and give recommendation to the user