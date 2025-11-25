 🎬 Movie Recommender System

A content-based movie recommendation system built using machine learning and deployed using Streamlit.  
This project helps users discover similar movies based on their selected preferences.

---

## 📌 Features

- Suggests movies similar to a selected movie
- Uses bag-of-words (CountVectorizer) for text vectorization
- Computes cosine similarity between movie descriptions
- Clean and interactive Streamlit UI
- Uses TMDB API posters for real-time images

---

## 📂 Project Structure

---


## 🧠 How It Works

### 1. **Data Preprocessing**
The dataset is cleaned and combined into a single `tags` column containing:
- Plot keywords  
- Genres  
- Cast  
- Crew  
- Overview  

### 2. **Text Vectorization**
`CountVectorizer` converts the text data into numerical vectors using the **bag-of-words model**.

### 3. **Similarity Computation**
Cosine similarity is calculated between all movie vectors to identify movies that are close to each other.

### 4. **Deployment**
The final model and similarity matrix are saved using `pickle`, and the app is deployed using Streamlit.

---

## 🚀 Installation

Clone this repository:

git clone https://github.com/your-username/movie-recommender-system.git


Install dependencies:

pip install -r requirements.txt


Run the Streamlit app:


---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- CountVectorizer  
- Cosine Similarity  
- Streamlit  
- Pickle  
- TMDB API  

---



## 👤 Author

  Shubhangi Chaurasia 


---

## 📄 License

This project is open-source and free to use.
