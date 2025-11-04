# Movie-Recommender-System

Developed a content-based movie recommender system using machine learning techniques.

Utilized a dataset from TMDb (The Movie Database) containing details like movie titles, overviews, genres, keywords, and cast.

Performed data preprocessing including feature extraction, text cleaning, and missing value handling.

Combined multiple text features into a single “tags” column to represent each movie's essence.

Applied CountVectorizer from scikit-learn to convert movie tags into a vectorized numerical format.

Used cosine similarity to compute similarity scores between movies based on their tag vectors.

Created a recommend() function that returns the top 5 most similar movies to a selected title.
