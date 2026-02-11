# 🎬 Movie Recommendation System

A Content-Based Movie Recommendation System built using Machine Learning and deployed with Streamlit. This project recommends similar movies based on textual features and dynamically fetches movie posters using the TMDB API.

---

## 🚀 Live Demo

👉 https://movie-recommender-system-gmxo498lbhns9sbdrmqwi7.streamlit.app/

---

## 🚀 Overview

This system uses Natural Language Processing techniques to analyze movie metadata such as overview, genres, keywords, cast, and crew. It converts textual data into numerical vectors using Bag of Words and calculates similarity using Cosine Similarity to recommend the top 5 most similar movies.

The web interface is built using Streamlit for an interactive user experience.

---

## 🧠 How It Works

• Combined important movie features into a single "tags" column  
• Converted text into numerical vectors using CountVectorizer  
• Applied Cosine Similarity to compute similarity scores  
• Recommended top 5 similar movies  
• Integrated TMDB API to fetch movie posters dynamically  

---

## 🛠️ Tech Stack

• Python  
• Pandas  
• NumPy  
• Scikit-learn  
• NLTK  
• Streamlit  
• TMDB API  

---

## 📂 Project Structure

movie-recommender-system/
- app.py  
- movies.pkl  
- similarity.pkl  
- requirements.txt  
- Procfile  
- setup.sh  
- README.md  

---

## 📦 Installation & Run Locally

Install dependencies:

pip install -r requirements.txt

Run application:

streamlit run app.py

---

## 🌐 Deployment

The application can be deployed using:

• Streamlit Cloud  

---

## 🎯 Key Highlights

• Content-Based Filtering  
• NLP-based Text Vectorization  
• Cosine Similarity Implementation  
• Dynamic Poster Fetching  
• Web Deployment Ready  

---

## 👩‍💻 Author

Darshika Hingu  
M.SC – Data Science  
Machine LearningEnthusiast 🚀
