#### Plot description-based recommender

Our plot description-based recommender will take in a "movie title" as an argument and output a list of movies that are most similar based on their plots. These are the steps we are going to perform in building this model:

<li>Obtain the data required to build the model</li>
<li>Create TF-IDF vectors for the plot description (or overview) of every movie</li>
<li>Compute the pairwise cosine similarity score of every movie</li>
<li>Write the recommender function that takes in a movie title as an argument and outputs movies most similar to it based on the plot</li>

