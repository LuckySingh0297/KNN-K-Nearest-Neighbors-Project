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

## 🔍 Insights
- Most features are not normally distributed.
- Features like `Ba`, `Fe`, and `K` are highly skewed.
- Some variables contain outliers and uneven spread.
- The target variable (`Type`) is imbalanced across classes.

---

# 📦 Boxplot Analysis

![Boxplot](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/boxplot.png)

## 🔍 Insights
- Multiple outliers are present in features like `Ca`, `Ba`, `Fe`, and `K`.
- Feature ranges are very different from each other.
- Scaling is necessary because KNN is distance-based.
- Outliers may affect distance calculations and model performance.

---

# 🔥 Correlation Heatmap

![Heatmap](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/heatmap.png)

## 🔍 Insights
- `RI` and `Ca` show strong positive correlation.
- `Mg` has strong negative correlation with `Type`.
- `Al` and `Ba` have positive influence on glass classification.
- Some features are weakly correlated, indicating independent behavior.

---

# 📉 Best K Value Selection

![Best K](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/Best%20K%20Value%20Selection.png)

## 🔍 Insights
- Highest cross-validation accuracy was achieved around lower K values.
- Model performance decreases as K becomes too large.
- Smaller K values capture local patterns better in this dataset.
- Optimal K value helps improve generalization and prediction accuracy.

---

# 📊 Confusion Matrix

![Confusion Matrix](https://github.com/LuckySingh0297/KNN-K-Nearest-Neighbors-Project/blob/main/Images/confusion_matrix(Actuall%20vs%20Prediction).png)

## 🔍 Insights
- The model correctly classified several glass types with good accuracy.
- Some classes were misclassified due to overlapping feature patterns.
- Minority classes are harder to predict accurately.
- Overall model performance is reasonable for multiclass classification.

---
