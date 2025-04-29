# ml_assignmentnetflix
# 🎬 Netflix Title Type Classifier

This project uses machine learning algorithms to classify Netflix titles as either **Movies** or **TV Shows** based on features like release year, duration, rating, country, and more.

---

## 📁 Dataset

- **Source**: [`netflix_titles_cleaned.csv`](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Cleaned version with missing values handled and date/duration parsed.

---

## 🔧 Features Used

- `release_year`
- `duration_int` (duration in minutes or seasons)
- `duration_unit`
- `rating`
- `country`
- `year_added`, `month_added`

---

## 🤖 Algorithms Implemented

| Model                  | Description                               |
|-----------------------|-------------------------------------------|
| Logistic Regression    | Baseline linear model                     |
| Decision Tree          | Non-linear model, prone to overfitting    |
| Random Forest          | Ensemble of trees, better generalization  |
| K-Nearest Neighbors    | Instance-based learning                   |

---

## 📉 Reduced Accuracy Testing

We deliberately tested the limits of each model by:
- Using minimal features
- Injecting noise into data
- Reducing dataset size
- Increasing model parameters (like `k` in KNN)

---

## 📊 Visualizations

- Confusion matrix heatmaps
- Accuracy comparison bar charts
- Classification reports

---

## 🧪 Requirements

Install dependencies using pip:

```bash
pip install -r requirements.txt
