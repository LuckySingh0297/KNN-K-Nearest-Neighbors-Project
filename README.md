# 🧪 Glass Type Classification using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This project uses the **K-Nearest Neighbors (KNN)** algorithm to classify different types of glass based on their chemical composition. The objective is to automate the glass classification process for a manufacturing company and reduce manual effort.

---

# 📂 Dataset Information

The dataset contains chemical properties of glass samples.

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
| Type | Glass Type (Target Variable) |

---

# 🎯 Business Problem

A glass manufacturing company wants to automate the process of classifying glass types based on chemical composition. Manual classification is time-consuming and inefficient.

The goal is to build a machine learning model that can accurately predict the type of glass.

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📊 Exploratory Data Analysis (EDA)

Performed:
- Data Cleaning
- Null Value Checking
- Duplicate Removal
- Statistical Summary
- Histograms
- Boxplots
- Correlation Heatmap

---

# 📈 Univariate Analysis

![Histogram](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/histogram(univariant%20analysis).png)

---

# 📦 Boxplot Analysis

![Boxplot](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/boxplot.png)

---

# 🔥 Correlation Heatmap

![Heatmap](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/heatmap.png)

---

# 🤖 Machine Learning Model

## Algorithm Used
- K-Nearest Neighbors (KNN)

## Steps Performed
- Feature Scaling using `StandardScaler`
- Train-Test Split
- Model Training
- Hyperparameter Tuning
- Cross Validation
- Model Evaluation

---

# 📉 Best K Value Selection

![Best K](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/Best%20K%20Value%20Selection.png)

Cross-validation was used to determine the optimal value of K for the KNN model.

---

# 📊 Confusion Matrix

![Confusion Matrix](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/confusion_matrix(Actuall%20vs%20Prediction).png)

The confusion matrix helps visualize the classification performance of the model by comparing actual vs predicted values.

---

# 📈 Model Evaluation

Evaluation metrics used:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 🔍 Why Scaling is Important in KNN

KNN works using distance calculations. Features with larger values can dominate smaller-valued features.

Feature scaling ensures all variables contribute equally during distance calculation.

---

# 🚀 Business Impact

- Reduces manual classification effort
- Improves operational efficiency
- Faster glass type prediction
- Reduces human error
- Helps maintain manufacturing quality

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

Install dependencies:

```python
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run Jupyter Notebook:

```python
jupyter notebook
```

---

# 📌 Conclusion

The KNN model successfully classified glass types using chemical composition data. Proper feature scaling and optimal K selection significantly improved model performance.

---

# 👨‍💻 Author

## Lucky Singh

Aspiring Data Scientist | Machine Learning Enthusiast
