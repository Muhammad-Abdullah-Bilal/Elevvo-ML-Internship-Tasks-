# 🎬 Movie Recommendation System using Collaborative Filtering

## 📌 Project Overview
This project is part of my **internship task** focused on building a **movie recommendation system**.  
The objective is to recommend relevant movies to users by analyzing **user behavior, similarity patterns, and latent features** extracted from historical ratings.

---

## 🧠 Covered Topics
- Recommendation Systems  
- Collaborative Filtering  
- User-Based Collaborative Filtering  
- Item-Based Collaborative Filtering  
- Matrix Factorization (SVD)  
- Precision@K Evaluation  

---

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

> **Note:** The implementation is done without external recommender libraries to better understand core concepts.

---

## 📂 Dataset
**MovieLens Dataset (Kaggle)**

### Files Used
- `movies.csv` – Movie metadata (movieId, title, genres)  
- `ratings.csv` – User ratings (userId, movieId, rating)  

Other files such as `links.csv` and `tags.csv` were not required for this task.

---

## 🔄 Workflow
1. Load movies and ratings data  
2. Split data into training and testing sets  
3. Create a user-item interaction matrix  
4. Compute cosine similarity  
5. Implement user-based collaborative filtering  
6. Implement item-based collaborative filtering  
7. Recommend top unseen movies for a user  
8. Evaluate models using Precision@K  
9. Apply Matrix Factorization using Truncated SVD  

---

## 📊 Models Implemented
- User-Based Collaborative Filtering  
- Item-Based Collaborative Filtering  
- Matrix Factorization (SVD)  

---

## 📈 Evaluation Metric
**Precision@K (K = 5)**  
Measures how many of the recommended movies are actually relevant to the user.

---

## 🎯 Results

| Model | Precision@5 |
|------|-------------|
| User-Based Collaborative Filtering | 0.2665 |
| Item-Based Collaborative Filtering | 0.0000 |
| SVD (Matrix Factorization) | **0.3164** |

---

## 🔍 Observations
- User-based filtering performs reasonably well when users share similar preferences  
- Item-based filtering struggled due to data sparsity  
- SVD captured latent patterns and achieved the **best performance**

---

## ▶ How to Run
1. Open **Google Colab**  
2. Upload `movies.csv` and `ratings.csv`  
3. Run all cells sequentially  
4. Modify `user_id` to generate recommendations for different users  

---

## ✅ Conclusion
This project demonstrates a **complete recommendation system pipeline** using collaborative filtering techniques.  
Among all approaches, **Matrix Factorization (SVD)** performed best and proved to be more scalable and accurate for real-world recommendation systems.