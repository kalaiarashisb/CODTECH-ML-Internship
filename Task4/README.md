# 🎬 Movie Recommendation System using Collaborative Filtering

## 📌 Project Overview

This project implements a **Movie Recommendation System** using **Collaborative Filtering** techniques.  
The system recommends movies based on user rating behavior using the **MovieLens dataset**.

The recommendation engine identifies movies with similar user rating patterns using **Cosine Similarity**.

---

# 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

# 📂 Dataset

Dataset Used:
- movies.csv
- ratings.csv

### movies.csv
Contains:
- movieId
- title
- genres

### ratings.csv
Contains:
- userId
- movieId
- rating
- timestamp

---

# 🧠 Machine Learning Concepts Used

- Collaborative Filtering
- Recommendation Systems
- User-Movie Matrix
- Cosine Similarity
- Data Preprocessing
- Similarity Metrics

---

# ⚙️ Project Workflow

1. Import required libraries
2. Load movie and ratings datasets
3. Merge datasets
4. Create user-movie matrix
5. Handle missing values
6. Apply cosine similarity
7. Generate movie recommendations
8. Visualize movie rating insights

---

# 📊 User-Movie Matrix

A pivot table was created where:
- Rows represent users
- Columns represent movies
- Values represent ratings

This matrix helps identify similar movies based on user preferences.

---

# 🔥 Collaborative Filtering

Collaborative filtering recommends movies based on:
- user interactions
- rating behavior
- similar viewing patterns

Example:
If users who liked *Toy Story* also liked *Jumanji*, the system recommends *Jumanji* to similar users.

---

# 📈 Cosine Similarity

Cosine similarity measures how similar two movies are based on user ratings.

### Similarity Range:
- 1 → Highly Similar
- 0 → Completely Different

---

# 📊 Data Visualization

The project includes:
- Most rated movies graph
- Dataset statistics
- Recommendation outputs

---

# 🔍 Key Insights

- Movies with similar rating patterns are recommended together.
- Collaborative filtering identifies hidden relationships between movies.
- User behavior plays a major role in recommendation systems.
- Recommendation systems improve user experience by suggesting relevant content.

---

# 🎯 Output

Example Recommendation:

Input:
```text
Toy Story (1995)
