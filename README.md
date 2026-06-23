# Heart Disease Prediction using Naive Bayes

## Project Overview

This Machine Learning project uses the Gaussian Naive Bayes algorithm to predict whether a patient is likely to have heart disease based on medical attributes.

The model is trained using the Heart Disease dataset and evaluated using standard classification metrics.

---

## Dataset Information

**Number of Records:** 303

### Features

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG (restecg)
* Maximum Heart Rate (thalach)
* Exercise Induced Angina (exang)
* ST Depression (oldpeak)
* Slope
* Number of Major Vessels (ca)
* Thalassemia (thal)

### Target

* 0 = Less chance of heart disease
* 1 = More chance of heart disease

---

## Technologies Used

* Python
* Pandas
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Train-Test Split
5. Train Gaussian Naive Bayes Model
6. Make Predictions
7. Evaluate Performance
8. Visualize Confusion Matrix

---

## Model Used

### Gaussian Naive Bayes

Gaussian Naive Bayes is a probabilistic classification algorithm based on Bayes' Theorem.

### Assumptions

* Features are independent of each other.
* Numerical features follow a normal (Gaussian) distribution.

---

## Results

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 86.89% |
| Precision | 90.00% |
| Recall    | 84.38% |

### Confusion Matrix

|          | Predicted 0 | Predicted 1 |
| -------- | ----------- | ----------- |
| Actual 0 | 26          | 3           |
| Actual 1 | 5           | 27          |

---

## Project Structure

```text
heart-disease-prediction-naive-bayes/
│
├── naive_bayes.ipynb
├── 1-heart.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/heart-disease-prediction-naive-bayes.git
```

Move into the project directory:

```bash
cd heart-disease-prediction-naive-bayes
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

* Hyperparameter Tuning
* Cross Validation
* Feature Engineering
* Model Comparison with Logistic Regression, KNN, and Random Forest

---

## Author

**Aryan Mestry**

BCA Student | Aspiring AI & ML Engineer | Open to Internship Opportunities
