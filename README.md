# 🎬 Movie Recommendation System

A simple **Movie Recommendation System** built using **Machine Learning and K-Nearest Neighbors (KNN)**.

The system recommends movies similar to a movie selected by the user by analyzing movie metadata.

## 🚀 Features

- 🎬 Movie-based recommendations
- 🤖 K-Nearest Neighbors (KNN)
- 🔎 Content-based recommendation
- 📊 Movie similarity using Cosine Distance
- 🧹 Data preprocessing
- 🐍 Python implementation
- 🌐 Streamlit web interface
- 🎯 Top similar movie recommendations

## 🧠 How It Works

```text
Movie Dataset
     │
     ▼
Data Preprocessing
     │
     ▼
Feature Extraction
     │
     ▼
Movie Feature Matrix
     │
     ▼
KNN Model
     │
     ▼
Similarity Search
     │
     ▼
Top Movie Recommendations
```

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Processing |
| Scikit-learn | Machine Learning |
| KNN | Recommendation Algorithm |
| CountVectorizer | Text Feature Extraction |
| Streamlit | Web Application |
| Pickle | Model/Data Storage |

## 📊 Dataset

This project uses the **TMDB 5000 Movie Dataset**.

Dataset files:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/vaibhavkatex/Katex-Moive-Recommendation-.git
cd Katex-Moive-Recommendation-
```

### 2. Create a Virtual Environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Or:

```bash
pip install pandas scikit-learn streamlit requests
```

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application normally opens at:

```text
http://localhost:8501
```

## 🧮 Machine Learning Algorithm

### K-Nearest Neighbors (KNN)

KNN finds movies that are closest to the selected movie in the feature space.

The system uses:

```text
KNN
+
Cosine Distance
```

Movie metadata is converted into numerical vectors, and KNN finds the nearest vectors.

## 🔄 Recommendation Pipeline

```text
Movie Dataset
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Text Vectorization
     ↓
Feature Matrix
     ↓
KNN
     ↓
Similarity Search
     ↓
Top Recommendations
```

## 📈 Future Improvements

- ⭐ User ratings
- 👤 Personalized recommendations
- 🎭 Actor-based recommendations
- 🎬 Director-based recommendations
- 🎞️ Movie posters
- 🔍 Search functionality
- 🌐 TMDB API integration
- 👥 Collaborative filtering
- 🧠 Hybrid recommendation system
- 🚀 Cloud deployment

## ⚠️ Limitations

1. The system mainly relies on movie content and metadata.
2. It does not deeply model individual user preferences.
3. New users have no interaction history.
4. Recommendation quality depends on feature quality.
5. KNN can become expensive with very large datasets.

## 💡 Learning Outcomes

This project demonstrates:

- Data preprocessing
- Feature engineering
- Text vectorization
- K-Nearest Neighbors
- Cosine similarity
- Content-based recommendation
- Streamlit development
- Basic ML deployment concepts

## 👨‍💻 Author

**Vaibhav Kate**

GitHub: https://github.com/vaibhavkatex

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

## 📜 License

This project is created for educational and learning purposes.
