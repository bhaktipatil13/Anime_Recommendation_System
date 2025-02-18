# Anime_Recommendation_System
Anime Recommendation System project

## 📌 Project Overview

This project implements a **content-based recommendation system** using **cosine similarity** on an anime dataset. The system suggests similar anime based on features such as genres, number of episodes, and user ratings.

---

## 📂 Dataset Description

The dataset contains information about various anime, including:

- **Anime\_ID**: Unique identifier for each anime.
- **Title**: Name of the anime.
- **Broadcast Type**: TV, OVA, Movie, etc.
- **Genre**: Anime genres such as Action, Romance, Fantasy, etc.
- **Episodes**: Number of episodes.
- **Rating**: Average user rating.
- **Members**: Number of users who have interacted with the anime.

---

## 🎯 Objective

The goal is to build a **recommendation system** that suggests similar anime based on cosine similarity scores.

---

## 🛠️ Implementation Steps

### 1️⃣ Data Preprocessing

- Load the dataset using **Pandas**.
- Handle **missing values**.
- Explore dataset structure and attributes.

### 2️⃣ Feature Extraction

- Select features for computing similarity (**genres, user ratings, etc.**).
- Convert categorical features into **numerical representations**.
- Normalize numerical features if needed.

### 3️⃣ Building the Recommendation System

- Compute **cosine similarity** between anime.
- Implement a function to **recommend similar anime** based on similarity scores.
- Experiment with different **threshold values** to fine-tune recommendations.

### 4️⃣ Evaluation

- Evaluate the recommendations using **precision, recall, and F1-score**.
- Analyze system performance and identify improvement areas.

---

## 📊 Technologies Used

- **Python** 🐍
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Scikit-learn** for cosine similarity
- **Matplotlib & Seaborn** for visualization

---

## 🚀 How to Run the Project

1️⃣ Clone the repository:

```bash
git clone https://github.com/your-username/anime-recommendation-system.git
cd anime-recommendation-system
```

2️⃣ Install dependencies:

```bash
pip install -r requirements.txt
```

3️⃣ Run the recommendation system:

```bash
python recommendation.py
```

---

## 📌 Results & Insights

- The recommendation system successfully suggests similar anime based on content similarity.
- Fine-tuning similarity thresholds improves recommendation quality.
- Future improvements can include **collaborative filtering** for enhanced recommendations.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 🔗 Connect with Me
📧 Email: bhaktipatil876@gmail.com

