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

- Movies make up [69.692833%] of Netflix's catalog, while TV Shows make up [30.307167%]
- Content additions peaked in [2019] with [2016] titles added
- [United States] and [India] are the top content-producing countries
- The most common genre is [International Movies]
- The most common rating is [TV-MA], suggesting [family-friendly / mature-audience] focus
- Average movie duration is around [99.58] minutes
- [Rajiv Chilaka ] has directed the most titles on the platform

## 📁 Project StructureS




## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook netflix.ipynb
```

## 👤 Author

Sahil Khan — [GitHub](https://github.com/Sahilkhxn)