# 🌸 Iris Flower Classification using Artificial Neural Network

A machine learning classification project that uses a **TensorFlow/Keras Artificial Neural Network (ANN)** to classify Iris flowers into three different species based on their sepal and petal measurements.

## 📌 Project Overview

The goal of this project is to build an Artificial Neural Network that can classify Iris flowers into:

- 🌱 Setosa
- 🌿 Versicolor
- 🌺 Virginica

The project covers the complete workflow from data preprocessing and visualization to ANN training and evaluation.

## 📊 Dataset

The project uses the **Iris dataset** containing four numerical features:

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal in cm |
| Sepal Width | Width of the sepal in cm |
| Petal Length | Length of the petal in cm |
| Petal Width | Width of the petal in cm |

### Target Classes

| Target | Species |
|---:|---|
| 0 | Setosa |
| 1 | Versicolor |
| 2 | Virginica |

After removing one duplicate row:

- **Total samples:** 149
- **Features:** 4
- **Classes:** 3
- **Missing values:** 0
- **Duplicate rows:** 0

## 🔍 Exploratory Data Analysis

The dataset was explored using:

- Target distribution
- Feature analysis
- Correlation analysis
- Data visualization

The target classes were almost perfectly balanced:

- Setosa → 50
- Versicolor → 50
- Virginica → 49

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

1. Removed duplicate rows.
2. Separated features (`X`) and target (`y`).
3. Split the dataset into training and testing sets.
4. Applied `StandardScaler` to the numerical features.
5. Applied one-hot encoding to the target classes.

### Dataset Split

```text
Training samples → 119
Testing samples  → 30
