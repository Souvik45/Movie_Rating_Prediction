# 🎬 Movie Rating Prediction using SVD

This project uses collaborative filtering with the Surprise library to predict user ratings for movies. It demonstrates the use of Singular Value Decomposition (SVD) to build a simple yet effective recommendation system.

## 📂 Dataset

- Source: [MovieLens (ratings.csv)](https://grouplens.org/datasets/movielens/)
- Columns: userId, movieId, rating, timestamp
- Preprocessing: timestamp column removed (not needed for rating prediction)


## 🚀 Features

- ✅ Data cleaning and preprocessing  
- ✅ Matrix Factorization using SVD  
- ✅ RMSE-based model evaluation  
- ✅ Prediction for individual user and movie  
- ✅ Visualization of rating distribution


## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- scikit-surprise (Surprise)
- Matplotlib, Seaborn
- Google Colab

## ⚙️ Steps Performed

1. Imported dataset (ratings.csv) and cleaned it  
2. Loaded dataset into Surprise using a custom Reader  
3. Split data into training and testing sets (80-20)  
4. Trained SVD model on training data  
5. Evaluated model using RMSE  
6. Predicted rating for a given user and movie  
7. Plotted distribution of movie ratings using Seaborn

---

## 📈 Results

- Achieved a good Root Mean Squared Error (RMSE) on test data
- Predicted how a user might rate a movie they haven’t watched yet
