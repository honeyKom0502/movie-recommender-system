#  Movie Recommendation System

A content-based Movie Recommendation System developed using Python and Machine Learning. The project recommends similar movies by analyzing features such as genres, keywords, cast, crew, and movie overview from the TMDB 5000 Movies dataset.

## Features

- Content-based movie recommendations
- Data preprocessing and feature engineering
- Merge movie and credits datasets
- Handle missing values
- Extract genres, keywords, cast, and director information
- Generate movie similarity using text vectorization
- Recommend similar movies based on cosine similarity

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook

## Dataset

- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset

## Machine Learning Concepts

- Data Preprocessing
- Feature Engineering
- Text Processing
- Stemming
- CountVectorizer
- Cosine Similarity

## Project Structure

```
Movie-Recommendation-System/
│── movie_recommendation.ipynb
│── tmdb_5000_movies.csv
│── tmdb_5000_credits.csv
│── README.md
```

## How to Run

1. Clone the repository.
2. Install the required libraries.

```bash
pip install pandas numpy scikit-learn nltk
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells to generate movie recommendations.

## Future Improvements

- Build a Streamlit web application
- Add poster images using the TMDB API
- Deploy the project online
- Improve recommendation accuracy using hybrid recommendation techniques

## Author

**Honey**
