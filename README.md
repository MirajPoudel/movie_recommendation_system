# 🎬 CinePickAI

A content-based movie recommendation system built using Python, Machine Learning, and Streamlit.  
It recommends movies based on similarity of genres, cast, crew, keywords, and overview, and uses the TMDB API to display movie posters and details.

---

# ✨ Features

- 🎯 Content-based movie recommendations  
- 🎥 Suggests similar movies based on metadata similarity  
- 🖼️ TMDB API integration for movie posters and details  
- ⚡ Fast and efficient recommendation system  
- 💻 Interactive Streamlit web interface  

---

# 🧠 How It Works

- Movie dataset is cleaned and preprocessed  
- Important features (genres, keywords, cast, crew, overview) are combined  
- Text is converted into vectors using ML techniques like CountVectorizer / TF-IDF  
- Cosine similarity is used to find similar movies  
- Top matching movies are recommended to the user .
---

# 🛠️ Technologies Used

- Python 🐍  
- Pandas 📊  
- Scikit-Learn 🤖  
- Streamlit 🌐  
- TMDB API 🎥  

---

# 🚀 Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
