# 🎬 Netflix Data Analysis (EDA)

Exploratory Data Analysis of Netflix's movies and TV shows dataset, exploring content trends, country-wise distribution, genres, ratings, and more.

## 📊 Dataset

- Source: [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/)
- ~8000+ titles with details like type, director, cast, country, release year, rating, and duration

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔍 Key Steps

1. Data cleaning — handled missing values in `director`, `cast`, `country`
2. Converted `date_added` to datetime and extracted year/month
3. Split `duration` into numeric values for movies (minutes) and TV shows (seasons)
4. Performed EDA across content type, country, genre, year, rating, and cast/crew

## 📈 Key Insights

- Movies make up [__%] of Netflix's catalog, while TV Shows make up [__%]
- Content additions peaked in [year] with [number] titles added
- [Country name] and [Country name] are the top content-producing countries
- The most common genre is [genre name]
- The most common rating is [rating], suggesting [family-friendly / mature-audience] focus
- Average movie duration is around [__] minutes
- [Director name] has directed the most titles on the platform

## 📁 Project Structure