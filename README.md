# 🎬 Movie Recommender System

A Machine Learning based Movie Recommendation System that recommends similar movies based on content similarity using Natural Language Processing (NLP) and Cosine Similarity.

The project uses the TMDB 5000 Movies Dataset and provides movie recommendations with posters using a Streamlit web application.

---

# 🚀 Features

* Movie recommendation based on similarity
* Content-based filtering
* Movie poster fetching using TMDB API
* Streamlit interactive web application
* Fast recommendation system
* NLP-based text processing

---

# 🛠️ Technologies Used

* Python
* Machine Learning
* NLP (Natural Language Processing)
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* Pickle
* TMDB API

---

# 📂 Dataset

Dataset used:

* tmdb_5000_movies.csv
* tmdb_5000_credits.csv

Dataset Source:

* TMDB Movie Metadata Dataset

---

# 🧠 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Text Vectorization
5. Cosine Similarity Calculation
6. Recommendation Generation
7. Web App Deployment

---

# 📊 Algorithms Used

* Count Vectorizer
* Cosine Similarity
* Content-Based Recommendation

---

# 📁 Project Structure

```bash id="fpr7p7"
Movie-Recommender-System/
│
├── model/
│   ├── movie_list.pkl
│   └── similarity.pkl
│
├── app.py
├── movies.ipynb
├── requirements.txt
├── README.md
└── dataset/
```

---

# ⚙️ Installation

## Step 1: Clone Repository

```bash id="9zvmva"
git clone https://github.com/your-username/movie-recommender-system.git
```

## Step 2: Move to Project Folder

```bash id="n8tlj4"
cd movie-recommender-system
```

## Step 3: Install Dependencies

```bash id="a2lxk6"
pip install -r requirements.txt
```

---

# ▶️ Run Streamlit App

```bash id="ol80e8"
streamlit run app.py
```

---

# 💡 How It Works

The system:

* Extracts movie tags from:

  * Overview
  * Genres
  * Keywords
  * Cast
  * Crew

* Converts text into vectors using:

  * CountVectorizer

* Calculates similarity using:

  * Cosine Similarity

* Recommends top 5 similar movies.

---

# 🎥 Example Recommendations

If you search:

```bash id="s7qgdr"
Avatar
```
---

# 🌐 Streamlit Interface

The web app allows users to:

* Select a movie
* View recommended movies
* Display movie posters

---

# 📈 Future Improvements

* Collaborative Filtering
* Deep Learning Recommendation System
* User Login System
* Movie Rating Prediction
* Deploy on Heroku or Render
* Add Search Autocomplete

---

# 📸 Project Output

The system displays:

* Recommended movie names
* Movie posters
* Similar movies list

---

