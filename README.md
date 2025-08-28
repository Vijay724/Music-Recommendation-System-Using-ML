# Music-Recommendation-System-Using-ML

## 🎵 Description

This project is a music recommendation system that uses machine learning techniques to suggest songs to users based on a Spotify dataset. The system analyzes various audio features of songs to identify similarities and group them into clusters, forming the basis for recommendations.

## 📊 Dataset

The project utilizes a comprehensive Spotify dataset, which is divided into the following files:

* **`data.csv`**: Contains audio features for a large number of songs.
* **`data_by_genres.csv`**: Provides audio features aggregated by genre.
* **`data_by_year.csv`**: Contains audio features aggregated by year.

The dataset includes a rich set of audio features for each song, such as:

* **Acousticness**: A measure of whether the track is acoustic.
* **Danceability**: Describes how suitable a track is for dancing.
* **Energy**: Represents a perceptual measure of intensity and activity.
* **Instrumentalness**: Predicts whether a track contains no vocals.
* **Liveness**: Detects the presence of an audience in the recording.
* **Loudness**: The overall loudness of a track in decibels (dB).
* **Speechiness**: Detects the presence of spoken words in a track.
* **Tempo**: The overall estimated tempo of a track in beats per minute (BPM).
* **Valence**: A measure describing the musical positiveness conveyed by a track.
* **Popularity**: The popularity of a track.

## ⚙️ Methodology

The project follows a structured approach to build the recommendation system:

### 1. Exploratory Data Analysis (EDA) 📈

The initial step involves a thorough exploratory data analysis to understand the dataset's characteristics. This includes:

* Visualizing the distribution of songs across different decades.
* Analyzing the evolution of audio features over the years.
* Comparing the audio characteristics of various music genres.

### 2. Clustering 🎶

The core of the recommendation system is built using the **KMeans clustering algorithm**. This unsupervised learning technique is used to:

* Group similar songs based on their audio features.
* Cluster different genres to understand their relationships.

To visualize the created clusters, the **t-SNE (t-Distributed Stochastic Neighbor Embedding)** technique is used to reduce the high-dimensional data into a 2D space.

## 🛠️ Installation

To run this project, you need to have Python installed along with the following libraries. You can install them using pip:

```bash
pip install numpy pandas seaborn plotly matplotlib scikit-learn yellowbrick
