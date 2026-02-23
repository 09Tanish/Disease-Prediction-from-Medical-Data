# 🩺 Disease Prediction from Medical Data

The **Disease Medical Model** is a Machine Learning–based system designed to predict the likelihood of multiple diseases such as:

* Breast Cancer
* Diabetes
* Heart Disease
* Lung Cancer

using structured patient health data.

This system acts as a **clinical decision-support tool** and is **not a replacement for professional medical diagnosis**.

---

## 📌 Overview

This project develops a robust Disease Prediction Model using structured medical datasets. The system supports multiple classification algorithms and enables accurate prediction based on patient input parameters such as:

* Age
* Blood Pressure
* Glucose Level
* Cholesterol
* Symptoms

---

## 🔄 System Flow

1. Input: Patient health data
2. Data Processing: Cleaning, normalization, feature engineering
3. Modeling: Training ML algorithms
4. Output: Disease likelihood prediction

---

## 🎯 Features

* Multi-Disease Prediction Support
* Multiple ML Algorithms:

  * Logistic Regression
  * Support Vector Machine (SVM)
  * Random Forest
  * XGBoost
* Tunable ML Pipelines
* Model Performance Comparison
* Comprehensive Evaluation Metrics

---

## 🧠 Tech Stack

| Layer     | Technology Used                                  |
| --------- | ------------------------------------------------ |
| Language  | Python                                           |
| Libraries | Scikit-learn, Pandas, NumPy                      |
| Models    | Logistic Regression, SVM, Random Forest, XGBoost |
| Notebook  | Jupyter Notebook                                 |
| Tools     | pip, venv                                        |

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/disease-prediction-model.git
cd disease-prediction-model
```

### 2️⃣ Create and Activate Virtual Environment

```bash
python -m venv venv
```

Activate environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/Mac:**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Step 1: Add Dataset

Place dataset files inside the `data/` directory:

Examples:

* heart.csv
* diabetes.csv

### Step 2: Train Model

```bash
python train.py --dataset data/heart.csv --model random_forest
```

### Step 3: Make Predictions

```bash
python predict.py --model output/random_forest.pkl --input data/new_samples.csv
```

---

## ⚙️ How It Works

* Data Loading & Cleaning: Handles missing values and normalization
* Feature Engineering: Improves model performance
* Model Training: Uses cross-validation
* Evaluation: Generates performance metrics
* Prediction: Trained model used for inference

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Curve

Use the provided Jupyter Notebook (`evaluation.ipynb`) for:

* Visualization
* ROC Curves
* Confusion Matrix

---

## 📂 Project Structure

```
disease-prediction-model/
│
├── data/
├── output/
├── train.py
├── predict.py
├── evaluation.ipynb
├── requirements.txt
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

## 📜 License

This project is developed for academic and research purposes only.

---

## 📬 Contact

**Tanish Bachuwar**
B.Tech Data Science
Woxsen University
