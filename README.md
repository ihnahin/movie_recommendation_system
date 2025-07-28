
---

## ✅ Project 2: `Movie Recommendation System (Content-Based)`

### 📄 `README.md`:

```markdown
# 🎬 Movie Recommendation System (Content-Based)

This is a simple content-based movie recommender system that suggests similar movies based on the description (overview) using TF-IDF and Cosine Similarity.

---

## 📌 Project Description

Using movie overviews and natural language processing, this project recommends 5 similar movies when you input a movie name. The similarity is calculated using TF-IDF vectors and cosine similarity.

---

## 🧠 Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Jupyter Notebook / Google Colab

---

## 📊 Dataset

The dataset is taken from Kaggle:  
🔗 [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

Files used:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

---

## 🛠️ Steps Performed

1. Loaded and merged movie and credits datasets
2. Cleaned and preprocessed the data
3. Used TF-IDF to convert text data (overview) into vectors
4. Calculated similarity between all movies using cosine similarity
5. Created a function to return top 5 similar movies based on a given title

---

## ✅ Sample Recommendation

If you input **"Inception"**, you may get:
- Interstellar  
- The Prestige  
- The Matrix  
- Minority Report  
- Shutter Island  

---

## 🚀 How to Run the Code

1. Open the notebook (`movie_recommendation_system.ipynb`) in Google Colab or Jupyter Notebook.
2. Upload both CSV files when prompted:
   - `tmdb_5000_movies.csv`
   - `tmdb_5000_credits.csv`
3. Run all cells step-by-step.
4. Use the `recommend_movie("Movie Name")` function to test.

---

## 👤 Author

**Md Ismail Hossain Nahin**  
Department of CSE  
Daffodil International University  
