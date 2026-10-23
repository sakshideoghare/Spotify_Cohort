# 🎧 Spotify Song Cohort Analysis
### Turning Music Data into Meaningful Listening Experiences

> **Can machine learning discover the listening experiences hidden inside song features?**

This project explores Spotify song data to identify meaningful groups of songs using audio characteristics, exploratory data analysis, dimensionality reduction, and unsupervised machine learning.

Rather than looking at songs only by artist, album, or popularity, the project investigates how features such as **danceability, energy, acousticness, loudness, tempo, and valence** can reveal patterns in music and support more meaningful playlist discovery.

---

## ✨ Project Highlights

- 🎵 **Music Data Exploration:** Investigated song characteristics, popularity patterns, album-level trends, and feature relationships.
- 🧹 **Data Preparation:** Cleaned the dataset and engineered additional features, including release year, duration in minutes, and a popularity indicator.
- 📊 **Exploratory Data Analysis:** Used visualizations and correlation analysis to understand relationships among audio features.
- 🧭 **Dimensionality Reduction:** Applied Principal Component Analysis (PCA) to explore the underlying structure of the audio-feature space.
- 🤖 **Unsupervised Learning:** Used K-Means and Hierarchical Clustering to discover groups of songs.
- 🎯 **Cluster Evaluation:** Explored the Elbow Method and Silhouette Score to support clustering decisions.
- 💡 **Business Interpretation:** Translated cluster characteristics into potential playlist and music-discovery use cases.

## 🎯 Problem Statement

Music platforms contain songs with diverse characteristics and listening experiences. Understanding these patterns can help organize music into more meaningful groups.

**Objective:** Discover song cohorts from audio features using unsupervised learning and interpret the resulting clusters in a practical music-discovery context.

## 🧠 The Approach

The project follows a structured data science workflow:

**Raw Data → Data Cleaning → Feature Engineering → EDA → PCA → Clustering → Cluster Profiling → Insights**

### 1. Data Understanding and Preparation
- Examined the dataset structure and relevant audio features.
- Prepared the data for exploratory analysis and clustering.
- Created additional analytical features, including release year and duration in minutes.

### 2. Exploratory Data Analysis
- Explored popularity distributions and album-wise popularity.
- Investigated relationships between energy, danceability, popularity, and other song attributes.
- Examined popularity trends over time.

### 3. Dimensionality Reduction
- Applied PCA to explore the structure of the selected audio features.
- Used dimensionality reduction as part of the clustering analysis workflow.

### 4. Clustering and Evaluation
- Applied K-Means clustering to identify groups of similar songs.
- Compared the results with Hierarchical Clustering.
- Used the Elbow Method and Silhouette Score to investigate suitable clustering configurations.
- Profiled the resulting clusters using their audio-feature characteristics.

### 5. Interpretation and Recommendations
Interpreted cluster profiles to develop understandable song-cohort categories and explore how these groups could support playlist organization and music discovery.

## 🎼 Song Cohorts

The analysis interprets song groups through the following listening-experience categories:

| Cohort | Intended interpretation |
|---|---|
| 🎉 Party Songs | Songs with characteristics associated with energetic, dance-oriented listening |
| 🎸 Acoustic Songs | Songs with stronger acoustic characteristics |
| 🎹 Instrumental Songs | Songs whose feature profiles may support instrumental-style listening |
| 😊 Happy Songs | Songs with characteristics associated with a positive or upbeat listening experience |

*These are interpretive labels for cluster profiles, not predefined ground-truth classes. Their meaning depends on the features observed in each cluster.*

## 🛠️ Technology Stack

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Techniques:** Exploratory Data Analysis, Feature Engineering, PCA, K-Means, Hierarchical Clustering
- **Evaluation:** Elbow Method, Silhouette Score
- **Environment:** Jupyter Notebook

## 📌 Key Takeaway

This project demonstrates how exploratory data analysis and unsupervised machine learning can be combined to investigate patterns in music data, compare clustering approaches, and translate technical outputs into understandable insights.

It reflects my practical learning in **Python, data analysis, feature engineering, dimensionality reduction, clustering, and data-driven interpretation**.

## 👩‍💻 Author

**Sakshi Prakash Deoghare**

Computer Science & Engineering | Aspiring Data Scientist & AI/ML Developer

[Connect with me on LinkedIn](https://www.linkedin.com/in/sakshi-deoghare-44969b274/)


