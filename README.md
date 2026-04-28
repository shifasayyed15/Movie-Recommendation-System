This project is a Movie Recommendation System that suggests movies similar to a user’s selected movie. The system is built using a content-based filtering approach, where recommendations are made by analyzing the features of movies rather than user behavior.

The model uses the TMDB 5000 movies dataset, which contains information such as genres, keywords, cast, and crew. These features are combined and processed using Natural Language Processing (NLP) techniques to create a meaningful representation of each movie.

To find similarity between movies, the system converts textual data into numerical vectors and applies cosine similarity. Based on this similarity score, the system recommends the top matching movies that are most related to the selected one.

A simple and interactive user interface is developed using Streamlit, allowing users to easily select a movie and get instant recommendations.
