# movie-recommendation-system-Project
🎬 Movie recommendation engine using content-based filtering and TF-IDF vectorization. Suggests top 5 similar movies based on input.

# 🎬 Movie Recommendation System using Machine Learning

A content-based movie recommendation engine that suggests similar movies based on descriptions, genres, cast, crew, and keywords.

---

## 🎯 Objective

- Suggest movies similar to a selected title
- Use content-based filtering (no user ratings needed)
- Vectorize movie metadata and find top 5 similar movies

---

## 📂 Dataset Overview

- Source: [TMDb (The Movie Database)](https://www.themoviedb.org/)
- Total Movies: ~4,800
- Features used: Titles, genres, cast, crew, overview, keywords

---

## ⚙️ Feature Engineering

- Merged all text features into a single column: `tags`
- Cleaned data using:
  - Lowercasing
  - Removing spaces
  - Tokenization
  - Stemming with NLTK

---

## 📐 Vectorization & Similarity

- Applied **TF-IDF Vectorizer** to convert text to vectors
- Removed stopwords
- Measured similarity using **cosine similarity**
- Retrieved top 5 most similar movie vectors

---

## 📥 Example Output

**Input**: _The Dark Knight_  
**Recommendations**:
- Batman Begins  
- The Dark Knight Rises  
- Joker  
- Man of Steel  
- Iron Man  

---

## 🛠️ Tools & Technologies

- Python, Pandas
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Jupyter Notebook

---

## 📁 Files Included

```bash
movie-recommendation-system/
│
├── ML_PROJECT_BY_Dixit_Movie_Recommendation.ipynb   # Full code
├── Movie_Recommendation_System_Presentation_Dixit_Jadav.pptx  # Slide deck
├── README.md                                          # Project summary
