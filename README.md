---

# 🚢 Titanic Survival Prediction

**CodSoft - Data Science Internship Project**

## 📌 Project Overview

The **Titanic Survival Prediction** project aims to analyze and predict the survival of passengers aboard the RMS Titanic, which tragically sank in 1912 after colliding with an iceberg. Leveraging historical passenger data (e.g., age, gender, class), this project builds a machine learning model to estimate the likelihood of survival for individuals on the ship.

---

## 📂 Dataset

* **Dataset Used**: [Titanic Dataset (Kaggle)](https://www.kaggle.com/competitions/titanic/data)
* Contains information such as:

  * `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## 🛠️ Tools & Libraries

* **Programming Language**: Python
* **Libraries**:

  * `Pandas` & `NumPy` - Data cleaning & manipulation
  * `Matplotlib` & `Seaborn` - Data visualization
  * `Scikit-learn` - Machine learning modeling & evaluation

---

## 📊 Project Pipeline

### 1. Exploratory Data Analysis (EDA)

* Understand feature distributions (e.g., Age, Fare, Gender)
* Visualizations to explore survival correlations:

  * Survival rate by gender
  * Survival rate by class
  * Age vs Survival distributions

### 2. Data Preprocessing

* Handling missing values (e.g., Age, Embarked)
* Encoding categorical variables (`Sex`, `Embarked`) using One-Hot Encoding
* Feature scaling (e.g., StandardScaler)
* Feature engineering (e.g., Family size from `SibSp` + `Parch`)

### 3. Model Selection & Training

* Models considered:

  * Logistic Regression ✅ (selected)
  * Decision Tree
  * k-Nearest Neighbors (k-NN)
* Logistic Regression was chosen for its:

  * Interpretability
  * Robustness
  * Good performance on binary classification

### 4. Model Evaluation

* Performance metrics:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
* Validation: Cross-validation used for robust evaluation

### 5. Deployment (Optional)

* Model ready for integration into a user-facing application (e.g., web app)
* Can make predictions on new/unseen passenger data

---

## 📈 Sample Visualizations

* Survival Count by Gender
* Fare vs Survival Scatter Plot
* Age Distribution Histogram
* Heatmap of Feature Correlation

---

## ✅ Results

* **Model Used**: Logistic Regression
* **Accuracy Achieved**: \~\[Insert your model accuracy here]%
* Insights:

  * Females had a significantly higher survival rate.
  * First-class passengers were more likely to survive.
  * Younger passengers had better chances of survival.

---

## 🚀 How to Run

1. Clone this repository

   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or script

   ```bash
   jupyter notebook titanic_prediction.ipynb
   ```

---

## 📚 Learnings

* Gained practical knowledge of real-world data preprocessing
* Understood the workflow of binary classification problems
* Developed skills in model selection, tuning, and evaluation
* Learned how to interpret logistic regression outputs

---
