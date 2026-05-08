# Sentiment Analysis using TF-IDF and Logistic Regression

## 📌 Project Overview
This project performs Sentiment Analysis on customer reviews using Natural Language Processing (NLP) techniques and Machine Learning algorithms.

The objective of this project is to classify customer reviews as:
- Positive Sentiment
- Negative Sentiment

The project uses:
- TF-IDF Vectorization
- Logistic Regression

for sentiment prediction.

---

# 📂 Dataset
Dataset used:
- `Restaurant_Reviews.tsv`

The dataset contains:
- Customer Reviews
- Sentiment Labels

### Dataset Columns
| Column | Description |
|---|---|
| Review | Customer review text |
| Liked | Sentiment label (1 = Positive, 0 = Negative) |

---

# 🛠 Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Seaborn

---

# ⚙️ NLP Preprocessing Steps
The following preprocessing techniques were applied:

- Convert text to lowercase
- Remove special characters
- Remove punctuation
- Tokenization
- Stopword removal
- Text cleaning using Regular Expressions

### Example

#### Original Review
```text
Wow... Loved this place!
```

#### Cleaned Review
```text
wow loved place
```

---

# 🔥 TF-IDF Vectorization
TF-IDF (Term Frequency - Inverse Document Frequency) converts textual data into numerical feature vectors.

This helps the machine learning model understand the importance of words in customer reviews.

---

# 🤖 Machine Learning Model
Model used:
```python
LogisticRegression()
```

Dataset split:
- Training Data → 80%
- Testing Data → 20%

---

# 📊 Model Evaluation

## Accuracy
The model achieved approximately:

```text
81% Accuracy
```

---

# 📈 Confusion Matrix

| Actual / Predicted | Negative (0) | Positive (1) |
|---|---|---|
| Negative (0) | 83 | 13 |
| Positive (1) | 35 | 69 |

---

# 🔍 Key Insights
- The model correctly classified most reviews.
- Negative reviews were predicted more accurately.
- TF-IDF successfully extracted important textual features.
- Logistic Regression performed effectively for sentiment classification.

---

# 🚀 Project Workflow

```text
Customer Reviews
        ↓
Text Preprocessing
        ↓
TF-IDF Vectorization
        ↓
Train-Test Split
        ↓
Logistic Regression
        ↓
Prediction
        ↓
Accuracy Evaluation
```

---

# ▶️ How to Run the Project

## Install Required Libraries
```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn
```

---

## Run Jupyter Notebook
Open the notebook file and run all cells.

---

# 📁 Project Structure

```text
Task2/
│
├── Sentiment_Analysis.ipynb
├── Restaurant_Reviews.tsv
├── README.md
```

---

# 🎯 Conclusion
This project demonstrates how Natural Language Processing and Machine Learning can be used to analyze customer opinions and classify sentiments automatically.

The combination of TF-IDF Vectorization and Logistic Regression achieved good performance and produced meaningful sentiment predictions from textual review data.

---

# 👨‍💻 Author
Kalaiarashi S B
