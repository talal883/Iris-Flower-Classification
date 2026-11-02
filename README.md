
# Iris Flower Classification 🌸

 ### End-to-End Machine Learning Classification Project

A Machine Learning classification project that predicts Iris flower species using four flower measurements. The project includes data preprocessing, exploratory data analysis, model training, evaluation, and prediction.

## Project Overview

This project classifies Iris flowers into three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The model uses four numerical features: sepal length, sepal width, petal length, and petal width.

## Dataset

- Source: Scikit-learn Iris Dataset
- Original Samples: 150
- Samples After Duplicate Removal: 149
- Input Features: 4
- Target Classes: 3
- Missing Values: 0
- Remaining Duplicates: 0

## Machine Learning Models

Three classification algorithms were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Model Performance

| Model | Test Accuracy |
|---|---|
| Logistic Regression | 96.67% |
| Decision Tree | 93.33% |
| Random Forest | 93.33% |

**Best Performing Model: Logistic Regression**

The best model achieved 96.67% accuracy on a test set of 30 samples.

## Exploratory Data Analysis

The project includes:

- Flower species distribution
- Feature distribution analysis
- Feature correlation heatmap
- Model accuracy comparison
- Confusion matrix

## Model Prediction

Example measurements:

- Sepal Length: 5.1 cm
- Sepal Width: 3.5 cm
- Petal Length: 1.4 cm
- Petal Width: 0.2 cm

**Predicted Species:** Iris Setosa

**Estimated Prediction Probability:** 97.84%

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Structure

```text
CodeAlpha_IrisFlowerClassification/
├── notebooks/
│   └── iris_classification_final.ipynb
├── models/
│   └── iris_logistic_regression.pkl
├── results/
│   ├── model_comparison.csv
│   ├── model_accuracy_comparison.png
│   ├── confusion_matrix.png
│   ├── species_distribution.png
│   ├── feature_distributions.png
│   └── correlation_heatmap.png
├── src/
├── data/
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone or download the repository.
2. Open the project folder in VS Code.
3. Install required dependencies:

```bash
pip install -r requirements.txt
```

4. Start Jupyter Notebook:

```bash
python -m notebook
```

5. Open `notebooks/iris_classification_final.ipynb`.
6. Run all cells sequentially.

## Author

Talal Ahmad

Python | Data Science | Machine Learning

## Project Purpose

This project demonstrates practical skills in data preprocessing, exploratory data analysis, machine learning classification, model evaluation, and prediction.
