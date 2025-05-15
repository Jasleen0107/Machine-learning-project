# 🎬 Movie Recommendation System
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
![Stars](https://img.shields.io/github/stars/Jasleen0107/machine-learning-project?style=social)
A content-based movie recommendation system built using Python and machine learning techniques. This project uses the TMDB 5000 movies dataset to suggest similar movies based on cast, crew, genres, and keywords.

📌 Features
1. Recommends movies similar to a given title
2. Uses content-based filtering (metadata-driven)
3. Cosine similarity and CountVectorizer for text matching
4. Cleaned and merged movie and credits datasets

🗃️ Dataset
Source: TMDB 5000 Movie Dataset on Kaggle

Files used:
1. tmdb_5000_movies.csv
2. tmdb_5000_credits.csv

🔧 Technologies Used
1. Python (Pandas, NumPy)
2. Scikit-learn (CountVectorizer, Cosine Similarity)
3. Jupyter Notebook

🚀 How to Run
1. Clone the repo:
git clone https://github.com/your-username/movies-recommendation.git
cd movies-recommendation
2. Install dependencies:
pip install -r requirements.txt
3. Run the notebook:
jupyter notebook MoviesRecommendation.ipynb

📈 Example Output
Input: Avatar
Recommended Movies:
1. Guardians of the Galaxy
2. John Carter
3. 2001: A Space Odyssey
4. Star Trek Into Darkness
5. The Hobbit

🧠 Future Enhancements
1. Use TF-IDF instead of CountVectorizer
2. Add movie posters and overviews in output
3. Build a web app with Flask or Streamlit
4. Incorporate collaborative filtering

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss
