
# 📚 Book Recommender System

**Book Recommender System** is an intelligent application built using Python that recommends books to users based on similarity scores, collaborative filtering, and user preferences. It leverages powerful libraries like **Pandas**, **NumPy**, and **scikit-learn** to deliver accurate and meaningful book suggestions.

> Designed and developed by **Sanika Dhumal** as part of a personal project in Data Science & Machine Learning.

---

## 🌟 Key Features

- 🔍 **Search-Based Filtering**: Find books similar to a selected title.
- 🤝 **Collaborative Filtering**: Suggest books based on user behavior.
- 📊 **Popularity-Based Recommendation**: Highlight top-rated and most-reviewed books.
- 🧠 **Cosine Similarity**: Core logic built on vectorized content similarity.
- 🖥️ Built using **Jupyter Notebook** with clean, modular code.

---

## 🛠️ Tech Stack & Libraries

| Tool/Library     | Purpose                          |
|------------------|----------------------------------|
| Python           | Core programming language        |
| Pandas           | Data loading and manipulation    |
| NumPy            | Numerical operations             |
| scikit-learn     | Vectorization and similarity     |
| Streamlit *(optional)* | Deploy as a web app             |
| Jupyter Notebook | Development environment          |

---

## 📁 Dataset Used

- **Books.csv** – Information about books (title, author, ISBN, etc.)
- **Users.csv** – User demographic information
- **Ratings.csv** – User ratings for books

> Source: [Book-Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/) or Kaggle version.



## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone 
cd book-recommender-system
````

### 2. Install Required Libraries

```bash
pip install pandas numpy scikit-learn
```

*(Optional for web version:)*

```bash
pip install streamlit
```

### 3. Run the Python Script

Use Jupyter Notebook or VS Code:

```bash
jupyter notebook book_recommender.ipynb
```

Or launch Streamlit web app:

```bash
streamlit run app.py
```

---

## ⚙️ How It Works

### 🔹 Popularity-Based Recommender

* Filters books with the highest number of ratings.
* Calculates average rating.
* Sorts and displays top N books.

### 🔹 Content-Based Filtering

* Vectorizes book titles using **CountVectorizer / TF-IDF**.
* Calculates cosine similarity between books.
* Recommends books similar to the selected title.

### 🔹 Collaborative Filtering (if implemented)

* Uses matrix factorization or KNN to suggest books based on user behavior.

---

## 📸 Sample Output

> *"You selected: Harry Potter and the Philosopher's Stone"*
> **Top Recommendations:**
>
> * Harry Potter and the Chamber of Secrets
> * Harry Potter and the Prisoner of Azkaban
> * Percy Jackson & The Olympians
> * Fantastic Beasts and Where to Find Them

---

## 📈 Performance Metrics

* Top-N accuracy based on user similarity (if collaborative filtering)
* Scalable to large datasets
* Fast similarity computations using sparse matrices

---

## 🧠 Learning Outcomes

* Data Preprocessing and Cleaning
* Building Recommendation Engines
* Similarity Measures (Cosine Similarity, KNN)
* Vectorization Techniques
* Deploying ML apps with Streamlit

---

## 🙋‍♀️ About Me

Developed by **Sanika Dhumal**, a Computer Science Engineering student passionate about data science, machine learning, and building intelligent apps.



---

## 📄 License

This project is licensed under the MIT License – feel free to fork and improve!

---

## 💡 Future Improvements

* Integrate deep learning-based recommendations.
* Add user login and personal dashboards.
* Deploy on Heroku / AWS / GCP with a frontend.


