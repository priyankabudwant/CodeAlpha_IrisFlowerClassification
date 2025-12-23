# CodeAlpha_IrisFlowerClassification
Data analyst project to classify Iris flowers using Python and scikit-learn
# Iris Flower Classification

## Project Overview
This project implements a machine learning solution to classify Iris flowers into three species: **Setosa, Versicolor, and Virginica**, based on their sepal and petal measurements.  

The goal is to build, evaluate, and compare multiple classification models while handling overfitting and performing hyperparameter tuning to achieve the best predictive performance.

---

## Dataset
- **Source:** Built-in `sklearn.datasets.load_iris`
- **Features:**
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target:** Species (Setosa, Versicolor, Virginica)

---

## Methodology

1. **Data Loading & Exploration**
   - Loaded Iris dataset
   - Explored basic statistics and correlations

2. **Model Training**
   - Logistic Regression with hyperparameter tuning (GridSearchCV)
   - Random Forest Classifier

3. **Cross-Validation**
   - Repeated Stratified K-Fold to ensure robust evaluation

4. **Evaluation Metrics**
   - Accuracy, Precision, Recall, F1-score
   - Overfitting handled by removing models with very high training recall

5. **Prediction**
   - Sample flower measurements were used to predict species using the trained models

---

## Key Libraries
- `pandas`  
- `numpy`  
- `scikit-learn`  
- `matplotlib` / `seaborn` (for visualization)

---

## Usage

1. Clone the repository:
```bash
git clone <your-github-repo-url>
