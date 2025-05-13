# Movie-recommender-system
This is a Movie Recommender System built using Streamlit. It suggests similar movies based on a selected movie using a content-based recommendation approach. The recommendations are powered by movie metadata and cosine similarity.

🚀 Demo
You can run the app locally or deploy it on platforms like Streamlit Cloud.

🧠 How It Works
The system uses cosine similarity on movie feature vectors to recommend 5 movies similar to the selected one.

Posters for the recommended movies are fetched using The Movie Database (TMDb) API.

🛠️ Tech Stack
Python

Pandas

Scikit-learn

Streamlit

TMDb API (for movie posters)

Pickle (for saving preprocessed data)

📦 Files in This Repository
File / Folder	Description

app.py - 	Main Streamlit application file

movie-dict.pkl	- Pickled dictionary of movie metadata

similarity.pkl	- Pickled similarity matrix (cosine similarity)

README.md -	Project documentation

