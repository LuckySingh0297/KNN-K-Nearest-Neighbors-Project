# 🧪 Glass Type Classification using K-Nearest Neighbors (KNN)

## 📌 Project Overview

This project focuses on building a **K-Nearest Neighbors (KNN)** classification model to predict different types of glass based on their chemical composition. The main objective is to automate the glass classification process for a manufacturing company and improve operational efficiency.

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Scaling
- KNN Model Building
- Hyperparameter Tuning
- Cross Validation
- Model Evaluation

---

# 🎯 Business Problem

A glass manufacturing company uses different chemical elements to produce various types of glass materials. Manual classification of glass types is time-consuming and inefficient.

The goal of this project is to develop a machine learning model that can accurately classify glass types automatically using chemical composition data.

---

# 📂 Dataset Information

The dataset contains chemical composition measurements of different glass samples.

## Features

| Feature | Description |
|---|---|
| RI | Refractive Index |
| Na | Sodium |
| Mg | Magnesium |
| Al | Aluminum |
| Si | Silicon |
| K | Potassium |
| Ca | Calcium |
| Ba | Barium |
| Fe | Iron |
| Type | Type of Glass (Target Variable) |

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 🧹 Data Preprocessing

Performed the following preprocessing steps:
- Checked missing values
- Removed duplicate records
- Performed feature scaling using `StandardScaler`
- Split data into training and testing sets

## 📌 Insight
- No major missing values were found in the dataset.
- Feature scaling was necessary because KNN is distance-based and sensitive to feature magnitude differences.

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand feature distributions, relationships, and outliers.

---

# 📈 Univariate Analysis

![Histogram](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/histogram(univariant%20analysis).png)

## 📌 Insight
- Most features showed skewed distributions.
- Some features such as `Ba`, `K`, and `Fe` had many values concentrated near zero.
- Glass types were unevenly distributed, indicating slight class imbalance.

---

# 📦 Boxplot Analysis

![Boxplot](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/boxplot.png)

## 📌 Insight
- Several outliers were detected in features like `Ba`, `Ca`, and `K`.
- Outliers may influence KNN distance calculations and affect model predictions.

---

# 🔥 Correlation Heatmap

![Heatmap](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/heatmap.png)

## 📌 Insight
- `RI` and `Ca` showed strong positive correlation.
- `Mg` had strong negative correlation with `Type`.
- `Al` and `Ba` showed moderate positive relationship with the target variable.
- Correlation analysis helped identify important predictive features.

---

# 🤖 Machine Learning Model

## Algorithm Used
- K-Nearest Neighbors (KNN)

## Why KNN?
KNN is a simple and effective supervised machine learning algorithm used for classification problems. It classifies data points based on the majority class among nearest neighbors.

---

# ⚡ Feature Scaling

Feature scaling was applied using `StandardScaler`.

## Why Scaling is Important in KNN?

KNN works using distance calculations. Features with larger numerical values can dominate smaller-valued features.

Scaling ensures:
- Equal contribution of all features
- Better distance calculation
- Improved model performance

---

# 📉 Best K Value Selection

![Best K](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/Best%20K%20Value%20Selection.png)

Cross-validation was used to determine the optimal value of K.

## 📌 Insight
- The highest cross-validation accuracy was achieved around **K = 2**.
- Accuracy gradually decreased as K increased.
- Smaller K values performed better for this dataset.

---

# 📊 Confusion Matrix

![Confusion Matrix](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/confusion_matrix(Actuall%20vs%20Prediction).png)

## 📌 Insight
- Some glass classes were predicted accurately.
- Certain classes showed misclassification due to overlapping feature distributions.
- The model performed well for majority classes but struggled slightly with minority classes.

---

# 📈 Model Evaluation

The following metrics were used:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Cross Validation Score
- Confusion Matrix

## 📌 Insight
- The model achieved moderate classification accuracy.
- Cross-validation helped improve generalization performance.
- Feature scaling significantly improved KNN prediction capability.

---

# 🚀 Business Impact

This solution provides several benefits to the manufacturing company:

- Reduces manual classification effort
- Improves operational efficiency
- Faster glass type prediction
- Reduces human error
- Helps maintain product quality
- Supports automation in manufacturing processes

---

# 📁 Project Structure

```bash
├── Images
├── glass.csv
├── KNN_Glass_Classification.ipynb
├── README.md
```

---

# ▶️ How to Run

## Install Dependencies

```python
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Run Jupyter Notebook

```python
jupyter notebook
```

---

# 📌 Conclusion

The K-Nearest Neighbors (KNN) model successfully classified different types of glass using chemical composition data. Proper feature scaling and optimal K-value selection played a critical role in improving model performance.

Exploratory Data Analysis helped identify important feature relationships, outliers, and class distribution patterns. Cross-validation improved model reliability and helped select the best hyperparameters.

This project demonstrates the practical application of machine learning in manufacturing automation and quality control.

---

# 👨‍💻 Author

## Lucky Singh

Aspiring Data Scientist | Machine Learning Enthusiast
