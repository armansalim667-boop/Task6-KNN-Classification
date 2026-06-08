# K-Nearest Neighbors (KNN) Classification

## 📌 Project Overview
This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for a classification problem using the **Iris Dataset**. The objective is to understand how KNN works, evaluate its performance with different values of K, and visualize the results.

---

## 🎯 Objective
- Understand the working of the KNN algorithm.
- Perform data preprocessing and feature normalization.
- Train and test a KNN classifier.
- Evaluate model performance using accuracy and confusion matrix.
- Experiment with different K values.
- Visualize model performance and decision boundaries.

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

---

## 📂 Dataset
**Iris Dataset**

The Iris dataset is a popular multiclass classification dataset containing:
- 150 samples
- 4 features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- 3 target classes:
  - Setosa
  - Versicolor
  - Virginica

Dataset source: Scikit-Learn built-in datasets.

---

## 🔄 Workflow

### 1. Import Required Libraries
Imported all necessary libraries for data handling, visualization, preprocessing, model training, and evaluation.

### 2. Load Dataset
Loaded the Iris dataset from Scikit-Learn.

### 3. Data Splitting
Split the dataset into:
- Training Set (80%)
- Testing Set (20%)

### 4. Feature Scaling
Applied **StandardScaler** to normalize features because KNN relies on distance calculations.

### 5. Model Training
Trained a KNN classifier using Scikit-Learn's `KNeighborsClassifier`.

### 6. Prediction
Predicted labels for the test dataset.

### 7. Model Evaluation
Evaluated the model using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 8. Hyperparameter Tuning
Tested multiple values of K and compared their accuracy.

### 9. Visualization
Generated:
- Accuracy vs K graph
- Decision Boundary visualization

---

## 📊 Results

### Accuracy Score
The model achieved high classification accuracy on the Iris dataset.

### Confusion Matrix
Used to analyze correct and incorrect predictions for each class.

### Accuracy vs K Plot
Shows how model accuracy changes with different K values.

### Decision Boundary
Visual representation of how KNN separates different classes.


