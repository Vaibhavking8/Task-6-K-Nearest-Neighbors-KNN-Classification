# Task-6-K-Nearest-Neighbors-KNN-Classification

This project demonstrates the use of the **K-Nearest Neighbors (KNN)** algorithm on the classic **Iris dataset** for classification. It includes data preprocessing, model training with multiple K values, evaluation, and visualization of decision boundaries.

## Dataset

The dataset used is `Iris.csv` which includes:
- **Features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target**: Species (Iris-setosa, Iris-versicolor, Iris-virginica)

## Tasks Performed

1. **Feature Normalization** using MinMaxScaler.
2. **Training** using `KNeighborsClassifier` from `sklearn`.
3. **Evaluation** across multiple values of **K** using:
   - Accuracy Score
   - Confusion Matrix
4. **Visualization**:
   - Accuracy vs K plot
   - Confusion Matrix heatmap
   - 2D decision boundary using two selected features
