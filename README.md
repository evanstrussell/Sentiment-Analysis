# 🧠 Sentiment Analysis of Employee Feedback

This project performs sentiment analysis on employee feedback to predict performance and potential ratings using natural language processing (NLP) and machine learning.

## 📂 Dataset

The dataset used in this analysis is sourced from Kaggle:

- 📊 **Notebook Source**: [Sentiment Analysis of Employee Review (Classic ML)](https://www.kaggle.com/code/fiodarryzhykau/sentiment-analysis-of-employee-review-classic-ml/notebook)

The dataset includes:
- **Feedback Text** – free-form employee reviews
- **Performance Score** – classified as `0 = low`, `1 = medium`, `2 = high`
- **Potential Score** – similarly classified as `0 = low`, `1 = medium`, `2 = high`

This is treated as a **multi-class text classification** problem.

## 🧠 Project Objectives

- Preprocess employee feedback for NLP tasks
- Perform exploratory text analysis
- Train machine learning models to predict:
  - Performance rating
  - Potential rating
- Evaluate model performance using classification metrics
- Identify key terms and sentiment drivers

## 🛠️ Tools & Libraries

The notebook uses the following Python libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `nltk` / `spaCy`
- `matplotlib`
- `seaborn`
- `re` / `string` for text processing

## 📁 Repository Structure

sentiment-analysis/
├── data/
│ ├── train_set.csv # Training data
│ ├── validation_set.csv # Validation data
│ └── test_set.csv # Test data
├── notebooks/
│ └── Sentiment_Analysis.ipynb # Main analysis notebook
└── README.md
