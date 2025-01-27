# netflix-content-analysis-
Analysis and clustering of Netflix movies and TV shows using Python.
# Netflix Movies and TV Shows Analysis and Clustering

## Overview
This project analyzes Netflix's content library to uncover trends and group similar content using clustering techniques. It combines exploratory data analysis (EDA) and machine learning to provide actionable insights into Netflix's content strategy.

---

## Goals
- **Exploratory Data Analysis (EDA)**: Identify patterns in Netflix's content library.
- **Clustering**: Group similar content based on descriptions and genres.

---

## Dataset
- **Source**: The dataset is sourced from Flixable (2019).
- **Content**: It contains 7,787 titles with attributes such as:
  - Title, Type (Movie/TV Show), Country, Date Added, Release Year, Director, Cast, Genre, and Description.

---

## Key Insights
### Movies vs. TV Shows Over Time
Netflix shifted focus from movies to TV shows after 2010, with TV shows dominating after 2015.

### Content Added Each Year
A sharp increase in content additions occurred between 2015 and 2019, aligning with Netflix's global expansion.

### Regional Content Distribution
- The United States dominates Netflix's library, followed by India, the UK, and Canada.
- India’s significant contribution reflects Netflix's efforts in regional markets.

### Genre Popularity
- Dramas, Comedies, and Documentaries are the most common genres, appealing to diverse audiences.

---

## Clustering Approach
- **TF-IDF**: Extracted key features from content descriptions.
- **K-Means**: Grouped content into clusters like Action Movies, Lighthearted Comedies, Family TV Shows, etc.
- **t-SNE**: Visualized clusters to identify separable themes.

---

## Technologies Used
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK
- **Clustering Algorithms**: K-Means and Agglomerative Clustering
- **Visualization**: PCA and t-SNE for cluster analysis

---




