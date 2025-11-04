# Movie-Recommender-System

Developed a content-based movie recommender system using machine learning techniques.

Utilized a dataset from TMDb (The Movie Database) containing details like movie titles, overviews, genres, keywords, and cast.

Performed data preprocessing including feature extraction, text cleaning, and missing value handling.

Combined multiple text features into a single “tags” column to represent each movie's essence.

Applied CountVectorizer from scikit-learn to convert movie tags into a vectorized numerical format.

Used cosine similarity to compute similarity scores between movies based on their tag vectors.

Created a recommend() function that returns the top 5 most similar movies to a selected title.

The model was built and tested in Jupyter Notebook for experimentation and visualization.

The final version was deployed using Streamlit (in PyCharm) as a web app where users can:

Select a movie from a dropdown list.

Instantly receive 5 similar movie recommendations with posters fetched dynamically via the TMDb API.

🚀 Key Learnings

Hands-on experience with NLP feature extraction, similarity metrics, and content-based filtering.

Practical understanding of end-to-end ML project development, from data processing to app deployment.

Integration of external APIs and web UI for an interactive machine learning application.
