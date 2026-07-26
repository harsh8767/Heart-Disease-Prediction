# ❤️ Heart Disease Prediction using Machine Learning

A Machine Learning project that predicts the likelihood of heart disease using patient medical records. The project compares multiple classification algorithms and evaluates their performance using various metrics.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals provide timely diagnosis and treatment.

In this project, Exploratory Data Analysis (EDA), data preprocessing, and multiple machine learning models are used to predict whether a patient has heart disease.

---

## 📂 Dataset

- **Dataset:** Heart Disease Dataset
- **Source:** Kaggle / UCI Machine Learning Repository
- **Records:** 303
- **Features:** 13
- **Target:** Presence of Heart Disease

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset Overview
- Missing Value Analysis
- Duplicate Value Check
- Descriptive Statistics
- Target Variable Distribution
- Age Distribution
- Heart Disease by Gender
- Chest Pain Type Distribution
- Cholesterol Distribution
- Age vs Maximum Heart Rate
- Correlation Heatmap

---

## ⚙️ Data Preprocessing

- Feature & Target Separation
- Train-Test Split
- Feature Scaling using StandardScaler

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

---

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve (AUC)

---

## 🏆 Results

| Model               |  Accuracy |
|--------             | ----------|
| Logistic Regression | **85.2%** |
| Decision Tree       | **75.4%** |
| Random Forest       | **83.6%** |

| **K-Nearest Neighbors (KNN)** | **90.2%** |

### Best Performing Model

🏆 **K-Nearest Neighbors (KNN)**

- Accuracy: **90.2%**
- Precision: **93.3%**
- Recall: **87.5%**
- F1-Score: **90.3%**

Logistic Regression achieved the highest ROC-AUC score (0.93), demonstrating excellent class-separation capability across different classification thresholds.

---

## 📂 Project Structure

```
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── heart.csv
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/harsh8767/Heart-Disease-Prediction.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Heart_Disease_Prediction.ipynb
```

---

## 📷 Output

The notebook includes:

- Exploratory Data Analysis
- Feature Importance Visualization
- ROC Curve Comparison
- Confusion Matrices
- Model Comparison Table

---

## 🔮 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- XGBoost and LightGBM Implementation
- Model Deployment using Streamlit
- Real-time Prediction Web Application

---

## 👨‍💻 Author

**Harsh Chavan**
GitHub : https://github.com/harsh8767

If you found this project useful, feel free to ⭐ the repository.
