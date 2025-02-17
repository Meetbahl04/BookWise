# 📚 Book Recommendation System

A **collaborative filtering-based** book recommendation system that suggests books based on user preferences. The system leverages **K-Nearest Neighbors (KNN)** and **cosine similarity** to find similar users and books, providing **personalized recommendations**.

## 🚀 Features
- **Data Preprocessing:** Cleans and filters user and book data for better recommendation quality.
- **Collaborative Filtering:** Uses user-item interactions to suggest relevant books.
- **Sparse Matrix Optimization:** Utilizes **SciPy’s CSR matrix** for efficient memory usage.
- **KNN-Based Recommendations:** Implements **scikit-learn’s NearestNeighbors** to compute similarity.
- **Precision & Recall Evaluation:** Measures the accuracy of recommendations using **evaluation metrics**.

## 📂 Dataset
The system uses the **Book-Crossing Dataset**, which includes:
- **Books Metadata** (Title, Author, Publisher, Year)
- **User Information** (Location, Age)
- **Ratings Data** (User-Book Interactions)

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, SciPy, scikit-learn)
- **Machine Learning** (KNN, Cosine Similarity)
- **Data Handling** (CSV Processing, Pivot Tables)

## 🎯 How It Works
1. Loads and cleans the book and user datasets.
2. Filters frequent users and popular books.
3. Constructs a **user-item matrix** for recommendations.
4. Uses **KNN with cosine similarity** to find similar books.
5. Provides recommendations based on user input.

## 🔍 Usage
Run the script and enter a book title to get recommendations:
```python
book_recommend('Animal Farm')
