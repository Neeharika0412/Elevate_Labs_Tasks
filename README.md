# 📊 Netflix Titles Dataset – Data Cleaning Project

## 📁 Dataset Info
- Source: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Contains data on Netflix's movies and TV shows, including title, cast, director, country, release year, rating, and date added.

## 🧹 Cleaning Summary

Performed using **Python (Pandas)** in **Google Colab**:

- Renamed columns to lowercase with underscores
- Removed duplicate rows
- Converted `date_added` to datetime format
- Filled missing `rating` with `'NR'` (Not Rated)
- Filled missing `director`, `cast`, and `country` with `'Unknown'`

## 📄 Files Included
- `netflix_titles_cleaned.csv` – Cleaned dataset
- `netflix_cleaning.ipynb` – Colab notebook with cleaning code
- `README.md` – This summary

## 🛠 Tools
- Python 3, Pandas, Google Colab
