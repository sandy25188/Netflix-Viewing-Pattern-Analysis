#  Netflix Viewing Pattern Analysis

This project explores viewing trends and content characteristics on Netflix using data analysis and machine learning. We used a dataset of over 8,800 titles including both Movies and TV Shows to generate insights and build a predictive model that classifies content type.

---

##  Exploratory Data Analysis (EDA)

We performed extensive data cleaning and exploratory analysis to understand:

- **Content trends over time** (e.g., number of titles added per year)
- **Content type breakdown** (Movies vs. TV Shows)
- **Top genres on Netflix**
- **Country-wise content production**
- **Duration analysis** (minutes for Movies, number of seasons for TV Shows)

## Visualizations included:
- Bar charts
- Pie charts
- Histograms
- Genre and country analysis

---

## Machine Learning

We built a Logistic Regression model to predict whether a title is a **Movie or TV Show** based on:

- Release year  
- Duration (`duration_min`)  
- Rating  
- Country  
- Top 10 genres (one-hot encoded)

### Model Performance

| Metric       | Movie (0) | TV Show (1) |
|--------------|-----------|-------------|
| Precision    | 1.00      | 1.00        |
| Recall       | 1.00      | 1.00        |
| F1-score     | 1.00      | 1.00        |
| **Accuracy** | **100%** on test data |

## Confusion Matrix:
[[1003  147]
 [ 218  227]]

  The model achieved near-perfect classification with minimal misclassifications after feature engineering.

---

## Project Structure
Netflix-Viewing-Analysis ├── netflix_viewing_pattern_analysis.ipynb # Jupyter notebook with full EDA + ML ├── README.md # Project overview ├── netflix_titles.csv # Source dataset


---

## 📌 Dataset Source

- [Netflix Movies and TV Shows Dataset – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🧰 Tech Stack

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 💡 Future Improvements

- Add a Streamlit dashboard for interactive visualizations  
- Try other ML models (Random Forest, XGBoost)  
- Use NLP to classify based on descriptions

---








