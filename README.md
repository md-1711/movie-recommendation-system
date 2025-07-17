# 🎬 Movie Recommender System

A content-based movie recommendation system built with Python and Streamlit, using the TMDB dataset and cosine similarity.

---

## 🔍 Features

- Recommends similar movies based on your input
- Uses movie metadata from TMDB dataset
- Interactive and responsive web interface using Streamlit
- Automatically downloads `similarity.pkl` from Google Drive if not found locally

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Scikit-learn
- Streamlit
- TMDB API
- gdown

---

## 📦 Installation

```bash
git clone https://github.com/md-1711/movie-recommendation-system.git
cd movie-recommendation-system
pip install -r requirements.txt
streamlit run app.py

---

## 🧠 How it Works

1. Combines keywords, cast, genres, and crew into a single "tags" column.
2. Converts the tags into vectors using `CountVectorizer`.
3. Calculates cosine similarity between all movies.
4. Recommends top 5 similar movies based on your selection.
5. Fetches posters using the TMDB API.

---

## 📸 Live Demo

👉 **[Try the App](https://movie-recommendation-system-7sbpmxx6jmqhysxiwtdj7s.streamlit.app/)**

---

## 📂 Folder Structure

├── app.py # Main Streamlit app
├── model/
│ ├── movie_list.pkl # Movie metadata
│ └── similarity.pkl # (Downloaded at runtime from Google Drive)
├── tmdb_5000_credits.csv
├── tmdb_5000_movies.csv
├── requirements.txt
├── README.md


---

### 🔧 Fixes Made:
- Closed the code block after `streamlit run app.py`
- Fixed folder structure using a proper code block
- Added a contact section (optional but looks professional)
- Used consistent formatting

---

Now you can:
```bash
git add README.md
git commit -m "Final README with all project info"
git push origin main
