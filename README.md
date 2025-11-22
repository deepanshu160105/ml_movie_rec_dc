# 🎬 Movie Recommendation System (TMDB Metadata)

## 📌 Project Overview

As a data & ML enthusiast, I built this **Movie Recommendation System** to practice working with real-world datasets, feature engineering, and deploying a simple app using **Streamlit**.

The app recommends movies similar to a selected one, using metadata from **TMDB (The Movie Database)** and a precomputed similarity matrix. It also fetches **movie posters** live using the TMDB API, giving a clean and interactive UI.

---

## 🎯 Objectives

- Build a simple, end-to-end **content-based recommendation system**
- Use a **real-world movie dataset** from Kaggle
- Serve recommendations through an **interactive Streamlit web app**
- Practice working with **pickled models**, APIs, and basic deployment structure

---

## 📂 Dataset

The project uses the official **TMDB Movie Metadata** dataset from Kaggle:

👉 [TMDB Movie Metadata – Kaggle Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

The dataset includes:

- Movie titles  
- TMDB IDs  
- Genres  
- Overviews and other metadata  

This metadata is used to engineer features offline and generate a similarity matrix for content-based recommendations.

---

## 🛠 Tech Stack

- **Python**
- **Streamlit** – for the web app UI
- **Pickle** – to load precomputed data and similarity matrix
- **Requests** – to call the TMDB API and fetch movie posters
- **Pandas / other ML libs** – used in the notebook to preprocess data and generate the similarity matrix (not directly in `app.py`)
