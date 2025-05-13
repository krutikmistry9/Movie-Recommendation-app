# 🎬 Movie Recommendation App

A **Content-Based Movie Recommender System** built using **TF-IDF** and **Cosine Similarity** on movie metadata.  
Built with **Python** and **Streamlit** for fast, interactive movie suggestions.

---

## 📌 Features

- 🎯 Content-based filtering using TF-IDF vectorization
- 📚 Cosine similarity on movie plot descriptions
- 🖼️ Movie poster & plot fetched using OMDb API
- ⚡ Interactive web interface using Streamlit

---

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt

```

Or install manually:

```bash
pip install streamlit==1.44.1 
numpy==2.2.4 
pandas==2.2.3 
scikit-learn==1.6.1 
nltk==3.9.1 
joblib==1.4.2 
requests==2.32.3
```

## 🚀 Getting Started

1. Preprocess the movie data:

```bash

cd src
python preprocess.py

```

2. Run the Streamlit app:

```bash

streamlit run main.py

```
## 🧠 How It Works

1. The system uses TF-IDF to convert movie plots into vectors.
2. It then calculates cosine similarity between the selected movie and all others.
3. The top 5 most similar movies are displayed with:
  I. Title
  II. Plot summary
  III. Poster image (via OMDb)

## 🖼️ App Interface

Select a movie from the dropdown list.

Click "🚀 Recommend Similar Movies".

View top 5 recommended movies with plots and posters.

## Screenshots

<img width="1440" alt="Screenshot 2025-05-13 at 3 22 14 PM" src="https://github.com/user-attachments/assets/8043c55e-36e3-4506-902d-f33f388d341b" />
<img width="1440" alt="Screenshot 2025-05-13 at 3 22 25 PM" src="https://github.com/user-attachments/assets/46f83017-fbab-4175-82e6-424878cd42f2" />

