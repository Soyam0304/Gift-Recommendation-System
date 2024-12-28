# Gift Recommendation System

## Overview
The Gift Recommendation System is a Python-based project that utilizes machine learning and data analysis techniques to recommend gifts based on user preferences and demographics. The system processes and cleans the dataset, performs clustering and similarity analysis, and visualizes key data insights to provide personalized gift suggestions.

## Features
- Data cleaning: Handles missing values and duplicates for accurate analysis.
- Clustering: Uses K-Means clustering to group similar users.
- Recommendation System: Utilizes TF-IDF Vectorizer and cosine similarity for recommendations.
- Visualizations:
  - Gender distribution pie chart.
  - Age distribution histogram.
  - Relationship and occasion frequency bar charts.

## Dataset
The system works with a CSV dataset that includes the following fields:
- **Gender**: Gender of the user.
- **Age**: Age of the user.
- **Relationship**: Relationship type for the gift.
- **Occasion**: Occasion for which the gift is intended.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
  - Text Analysis: `TfidfVectorizer`, `cosine_similarity`
  - Clustering Visualizer: `yellowbrick`

