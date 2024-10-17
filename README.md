#Movie Recommender System

This project is a Movie Recommender System built using Streamlit and Python. The application suggests movies based on user input, displaying similar movie recommendations along with their posters. The similarity between movies is calculated using a precomputed similarity matrix, and the movie data is loaded using pickle.

Demo
Check out the live demo of the app on [https://moviesystem-th5fsbr89efipszsghgzte.streamlit.app].

Features
User can select a movie from a dropdown list.
Recommends 5 similar movies based on the selected movie.
Displays posters of the recommended movies fetched via The Movie Database (TMDb) API.

Data
The movie data used for this recommendation system is preprocessed and stored in pickle format (movie_dict.pkl). The similarity matrix (similarity.pkl) is also precomputed and used to find similar movies.

Technologies Used
Streamlit: Used for building the web application.
Pandas: Data manipulation and analysis.
Pickle: For loading precomputed data (movies and similarity matrix).
Requests: Fetching movie posters from The Movie Database (TMDb) API.
Python: Main programming language for building the recommendation system.
