# Song Cohort Analysis and Clustering on Spotify Dataset

## Overview
This project aims to enhance song recommendations by analyzing and clustering songs from the Rolling Stones' albums on Spotify. By creating cohorts of similar songs, the project facilitates better understanding of the factors influencing song grouping, which can ultimately improve user engagement and satisfaction on Spotify.

## Problem Statement
Customers on platforms like Spotify expect personalized recommendations that align with their preferences. This project focuses on analyzing the Rolling Stones' songs dataset to:
- Perform exploratory data analysis (EDA) to identify key patterns.
- Create clusters of songs based on relevant features.
- Understand relationships between song popularity and other factors.

## Objective
As a data scientist, the goal is to:
1. Analyze and clean the dataset.
2. Perform EDA to uncover meaningful insights.
3. Implement clustering to create song cohorts.
4. Recommend strategies to improve song recommendations based on findings.

## Dataset Description
The dataset includes data from Spotify's API for all Rolling Stones albums available on Spotify. Each song is uniquely identified by a `song ID` and is associated with features such as:
- Popularity
- Tempo
- Energy
- Valence
- Acousticness
- Loudness
- Danceability

## Steps Performed

### 1. Data Inspection and Cleaning
- Identified and rectified duplicates, missing values, and outliers.
- Removed irrelevant entries and erroneous data points.
- Refined the dataset for further processing.

### 2. Exploratory Data Analysis and Feature Engineering
- Conducted visualizations to identify the two most recommended albums based on the number of popular songs.
- Analyzed relationships between song popularity and features like tempo, energy, and valence.
- Explored the evolution of popularity trends across features.
- Assessed the importance of dimensionality reduction techniques to improve clustering performance and reduce noise.

### 3. Clustering Analysis
- Determined the optimal number of clusters using methods like the elbow method and silhouette score.
- Applied clustering algorithms such as K-Means and Hierarchical Clustering.
- Defined each cluster based on characteristics like popularity, energy, and tempo.

## Key Insights
1. Albums with the highest number of popular songs were identified and recommended.
2. Popular songs exhibit unique patterns based on features such as tempo and energy levels.
3. Dimensionality reduction techniques, such as PCA, effectively highlighted critical song features, enhancing clustering results.
4. Clusters represented distinct song types, such as high-energy rock anthems or mellow ballads.

## Tools and Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Clustering Algorithms**: K-Means, Hierarchical Clustering
- **Dimensionality Reduction**: Principal Component Analysis (PCA)

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/spotify-song-clustering.git
   cd spotify-song-clustering
