# Movie Recommendation System

# Project Overview

This project invlolves building movie recommendation system using the MovieLens dataset. The system predicts top movie recommendations 
for users based on their previous ratings and explores advanced techniques like collaborative filtering and hybrid approaches to improve recommendation accuracy.

# Business understanding

Paramount studios would like to increase their viewship and user traffic on their paramount plus platform. TO increase engagement, they want to recommend certain movie titles to their current user and new user based.

In order to determine the best movies for users, we will create a recommendation system based on users viewship history for current subscribers, and possible recommedations for new accounts who signed up for the platform.

# Data and Methodology

Data used for this project is obtained from MovieLens, which contains explicit user ratings for movies along with metdata such as titles, genres, and timestamps. 

The data contains three datasets that we will use to create our recommendation system:
1.  Links.csv: maps movieId to external IDs. (9,743 imdbID and tmbdID)
2.  Movies.csv: Contains movie metadata, title, and genres. (9,743 movie selections)
3.  ratings.csv: Includes user ratings of movies, with columns: userId, movieId, rating, and timestamp. (100,000+ reported ratings)

Visualizations can be found in the "movie_recommendation_system" notebook.

The datasets can located in the following link:

[MovieLens](https://grouplens.org/datasets/movielens/latest/)

# EDA

During my initial analysis, I analyzed user and movie statistics. Visualized sparsity and distribution of ratings. Then plotted a heatmap of user-movie ratings to identify patterns.

# Models

![Distribution_of_ratings](./images/Distribution_of_ratings.png)

![Genre_distribution](./images/Genre_distribution.png)



# Conclusion

# Next Steps

# For more information

See the full analysis in the [Jupyter Notebook](https://github.com/omendez930/Phase4-movie-recommendation/blob/main/movie_recommendation_system.ipynb) and [Presentation]()

If you're interested in the visualizations, you can check it out here: [Tableau link](https://public.tableau.com/app/profile/orangel.mendez/viz/Movie_recommendation_system/Dashboard1?publish=yes)

Orangel Mendez: <omendez30@gmail.com>