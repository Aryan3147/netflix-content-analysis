# 🎬 Netflix Content Optimization with Machine Learning

This project explores and analyzes Netflix’s content catalog to uncover patterns in content type, genre trends, country distribution, and title metadata — and further applies **Machine Learning** to predict the popularity of titles based on their features.

The project is a combination of **Exploratory Data Analysis (EDA)** and **ML modeling**, using open data and Python to deliver insights that could support **region-specific recommendations and licensing strategies** for platforms like Netflix.

---

## 📁 Dataset

- **Source:** [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File:** `netflix_titles.csv`
- **Records:** ~6,000 titles including:
  - Title, Director, Cast
  - Type (Movie/TV Show)
  - Release Year, Date Added
  - Country, Rating
  - Duration, Genres

---

## 🎯 Objectives

- Analyze content trends: types, genres, countries, durations
- Discover patterns in yearly content additions
- Identify top contributors (directors, countries)
- Engineer features from textual data (genres, countries, cast)
- Build a **classification model** to predict content popularity
- Prepare dataset for future use in **recommendation systems** or **clustering**

---

## 🧰 Tools & Libraries

- **Python**
  - `pandas`, `matplotlib`, `seaborn`, `wordcloud`
  - `sklearn` for ML models and evaluation
- **Jupyter Notebook**
- Optional: `Streamlit` (for future dashboard)

---

## 🔍 Machine Learning Highlights

### ✅ Feature Engineering
- Converted multi-genre and country data into one-hot encoded features
- Extracted numeric fields like movie duration, year added
- Created a binary target variable `is_popular` based on cast, director, and country

### ✅ Modeling
- Trained a **Random Forest Classifier** to predict popularity
- Evaluated performance with accuracy score, confusion matrix, and classification report
- Analyzed feature importance to understand what drives content success

---

## 📊 Key Insights

- 📺 Netflix still favors movies over TV shows (~70% movies)
- 🗓️ Peak content additions occurred in 2019–2020
- 🎭 Genres like Drama, Comedy, and International Movies dominate
- 🌍 Top producing countries: USA, India, UK, Canada
- 🎬 Directors like Jay Karas and Raoul Peck are frequent contributors
- ⏱️ Most movies fall between 80–100 minutes
- 💡 Certain genre + country + director combinations strongly correlate with content popularity

---

## 📌 Visual Highlights

- Bar plots for type and genre distributions
- Countplots for content additions over time
- Horizontal bar charts for top genres, countries, directors
- Histograms for movie duration
- Word cloud built from title keywords
- Confusion matrix and feature importance from ML model

---

## 🤖 ML Model Performance

- **Model Used:** Random Forest Classifier
- **Accuracy:** ~100% *(Flagged as likely due to class imbalance or leakage; further tuning needed)*
- **Metrics:** Precision, Recall, F1-Score (via classification report)

---

## 🧪 Future Work

- Refine the `is_popular` target with real or simulated engagement data
- Implement KMeans clustering to group content by genre/country clusters
- Deploy a **recommendation engine** using cosine similarity or collaborative filtering
- Build an interactive dashboard using **Streamlit**
- Perform **NLP on title or description fields** for content tagging

---

## 🙏 Acknowledgments

> 💬 This project was conceptualized and built with the helpful guidance of [ChatGPT](https://chat.openai.com) by **OpenAI**.  
> Prompt-based support was used throughout:
> - ML model design and training
> - Code debugging and optimization
> - Documentation and reporting structure

---

## 💻 Author

- **Aryan Gaikwad**  
  Final Year B.E. (Computer Engineering) Student  
  📍 India

---
