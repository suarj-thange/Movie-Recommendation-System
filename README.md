# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built with Python and Machine Learning techniques. The system recommends movies similar to a user's favorite movie by analyzing movie attributes such as genres, keywords, tagline, cast, and director.

## 📌 Project Overview

Finding movies similar to your favorite movie can be difficult when there are thousands of options available.

This project uses a **content-based filtering approach** to identify movies with similar characteristics. The system converts selected movie features into numerical representations using **TF-IDF Vectorization** and calculates similarity between movies using **Cosine Similarity**.

Users can enter a movie name, and the system finds the closest matching title and generates a ranked list of similar movies.

---

## 🎯 Objectives

- Build a content-based movie recommendation system.
- Analyze movie metadata to identify similarities between movies.
- Apply TF-IDF for text feature representation.
- Calculate movie similarity using cosine similarity.
- Handle incomplete movie data before model processing.
- Allow users to enter movie names and receive recommendations.

---

## ✨ Key Features

- 🎬 Content-based movie recommendations
- 🔍 Movie title matching using `difflib`
- 🧹 Missing-value handling
- 📝 Text feature processing using TF-IDF
- 📐 Cosine similarity-based recommendations
- 📊 Analysis of movie metadata
- 💻 Interactive input through a Jupyter Notebook

---

## 🧠 How the System Works

### 1. Load the Dataset

The project loads the movie dataset using Pandas.

The dataset contains:

- **4,803 movies**
- **24 attributes**

Important attributes include:

- Genres
- Keywords
- Tagline
- Cast
- Director
- Title
- Rating
- Popularity
- Runtime
- Revenue
- Budget

### 2. Select Relevant Features

The recommendation system uses the following five features:

```text
genres
keywords
tagline
cast
director
