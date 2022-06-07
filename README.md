# Movie Recommendation System
  ## Tools used 

![Python](https://img.shields.io/badge/Python-3.8-FFD59E)

![API](https://img.shields.io/badge/API-TMDB-7D1E6A)

[![PyPI version shields.io](https://img.shields.io/pypi/v/trains-jupyter-plugin.svg)](https://img.shields.io/pypi/v/trains-jupyter-plugin.svg)

This is a Movie Recommendation system based on similarity based filtering using KNN Algorithm .

I used **[tmdb movie data set](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)** 

In this website, I have developed two types of recommendation engine one is based on the movies and other is based on the genre of movies.
#### Case-1: 
   (Movie-based) First select movie-based option from the drop down menu. Then type or choose a movie name from the list of movies and it will provide the name  and if you tap on the movie name it will direct you to the imdb page of that movie. You can also choose the number of movies you want as recommnedation.
#### Case-3:
   (Genre-based) First select genre-based option from the drop down menu. Then choose the genres you want recommendations for(you can select multiple genres from the drop down menu). Then you can also filter your recommendations on the basis of imdb score.You can also choose the number of movies you want as recommnedation. It will provide the name  and if you tap on the movie name it will direct you to the imdb page of that movie.

NOTE: You will get minimum 5 movie recommendations and a maximum of 20 movie recommendations!

## How does the project works 

   How does it decide which item is most similar to the item user likes? 
   So, I have used KNN Algorithm for that it basically maps all data points and gives you the k nearest datapoints to the searched item.In my website, you can set the value of from 5 to 20 (endpoints included) .
   
   This algorithm is used to solve the classification model problems. K-nearest neighbor or K-NN algorithm basically creates an imaginary boundary to classify the data. When new data points come in, the algorithm will try to predict that to the nearest of the boundary line.

Therefore, larger k value means smother curves of separation resulting in less complex models. Whereas, smaller k value tends to overfit the data and resulting in complex models.

   ### How KNN Algorithm works?
  KNN works by finding the distances between a query and all the examples in the data, selecting the specified number examples (K) closest to the query, then votes for the most frequent label (in the case of classification) or averages the labels (in the case of regression).

## How to use

1. Clone this repository to your local machine.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/shellysharma114/Movie-Recommendation-App/blob/main/requirements.txt) file with the command `pip install -r requirements.txt`
4. Open your terminal/command prompt from your project directory and run the file `app.py` by executing the command `streamlit run app.py`.


Thankyou for visiting!
