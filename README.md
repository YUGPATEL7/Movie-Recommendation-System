# Movie Recommender System
A content-based movie recommender system built using Machine Learning and deployed with Streamlit. It suggests similar movies based on selected movie preferences using text similarity and cosine similarity techniques.

##Features
Recommends 5 similar movies based on user input

Fetches movie posters using the TMDB API

Uses content-based filtering with NLP

Streamlit-based interactive UI

## Tech Stack
Python

Pandas, NumPy

Scikit-learn (CountVectorizer, Cosine Similarity)

Streamlit

TMDB API

Pickle for model serialization

📂 Project Structure
bash
Copy
Edit
├── app.py                  # Streamlit app
├── movie_list.pkl          # Processed movie data
├── similarity.pkl          # Cosine similarity matrix
├── tmdb_5000_movies.csv    # Raw movies dataset
├── tmdb_5000_credits.csv   # Raw credits dataset
