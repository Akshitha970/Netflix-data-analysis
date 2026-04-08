# 🎬 Netflix Data Analysis & Recommendation System

## 📌 Project Overview

This project performs an in-depth analysis of Netflix’s content library to uncover trends, build a recommendation system, and predict future popular genres using machine learning techniques.

It combines **data analysis, visualization, and predictive modeling** in a single end-to-end workflow using Python.

---

## 🚀 Key Features

### 🔹 Data Cleaning & Preprocessing

* Handled missing values in key columns (director, cast, country)
* Converted date formats for time-based analysis
* Created combined text features for recommendation system

### 🔹 Exploratory Data Analysis (EDA)

* Analyzed distribution of Movies vs TV Shows
* Identified top content-producing countries
* Explored year-wise growth of Netflix content
* Examined genre distribution patterns

### 🔹 📊 Data Visualization

* Static visualizations using Matplotlib & Seaborn
* Interactive charts using Plotly
* Animated genre trends over time

### 🔹 🎯 Recommendation System

* Built a **content-based recommendation system** using:

  * TF-IDF Vectorization
  * Cosine Similarity
* Recommends similar titles based on genre, description, and title

### 🔹 ⭐ IMDb Rating Integration (Optional)

* Merged IMDb dataset to enhance analysis
* Identified top-rated Netflix content

### 🔹 🔮 Machine Learning Prediction

* Implemented **Linear Regression model**
* Predicted most popular genres for the upcoming year

### 🔹 💾 Data Export

* Saved cleaned dataset for future use

---
## 📥 Dataset

Download the dataset from Kaggle:
https://www.kaggle.com/datasets/ashfakyeafi/netflix-movies-and-shows-dataset

## 🛠 Tech Stack

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:**

  * Pandas, NumPy
  * Matplotlib, Seaborn
  * Plotly
  * Scikit-learn
  * ipywidgets

---

## 📂 Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Analysis.ipynb
├── netflix_titles.csv
├── netflix_cleaned.csv
├── README.md
└── images/
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/netflix-data-analysis.git
cd netflix-data-analysis
```

### 2️⃣ Install Dependencies

```
pip install pandas numpy matplotlib seaborn plotly scikit-learn ipywidgets
```

### 3️⃣ Run the Project

```
jupyter notebook
```

Open `Netflix_Analysis.ipynb` and run all cells.

---

## 📊 Results & Insights

* Movies dominate Netflix content compared to TV Shows
* The United States contributes the highest number of titles
* Significant growth in content production after 2015
* Drama and International genres are the most common
* Predictive model highlights future trending genres

---

## 🖼️ Sample Outputs

### Movies vs TV Shows

![Movies vs TV Shows](images/chart1.png)

### Top Countries

![Top Countries](images/chart2.png)

### Recommendation System

![Recommendation](images/recommend.png)

### Genre Trends

![Genre Trends](images/chart3.png)

---

## 🔮 Future Enhancements

* Build a Streamlit web application
* Integrate real-time IMDb API
* Use advanced ML models (Random Forest, XGBoost)
* Deploy on cloud platforms

---

## 👩‍💻 Author

**Akshitha Gurram**

* Data Analyst | Python | SQL | Power BI | Machine Learning

---

## ⭐ Support

If you found this project useful, please ⭐ the repository and share your feedback!
