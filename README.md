Decision Tree Classifier on Iris Dataset
📌 Overview

This implements a Decision Tree Classifier using the Iris dataset from Scikit-learn.
Decision Trees are supervised machine learning algorithms used for classification and regression tasks. They work by splitting the data based on feature values to create a tree-like model of decisions.

Advantages:

Easy to understand and interpret

Handles both numerical and categorical data

No need for feature scaling

Disadvantages:

Can overfit if the tree grows too deep

Sensitive to small variations in data

📂 Dataset

Source: Iris dataset (from scikit-learn)

Classes:

Setosa (0)

Versicolor (1)

Virginica (2)

Features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Samples: 150

🛠️ Implementation Steps

Load the Iris dataset from Scikit-learn

Convert to pandas DataFrame

Split data into train (80%) and test (20%) sets

Train Decision Tree Classifier (DecisionTreeClassifier)

Use criterion="gini" (or "entropy")

Set max_depth to control overfitting

Predict on test data

Evaluate using:

Accuracy

Confusion Matrix

Classification Report

Visualize the decision tree using plot_tree()

(Optional) Plot confusion matrix heatmap using Seaborn

📊 Evaluation

Accuracy: ~96% (on Iris dataset)

Confusion Matrix: Shows correct vs misclassified classes

Classification Report: High precision, recall, and F1-score for all three classes

Example Confusion Matrix:

[[10  0  0]
 [ 0 10  1]
 [ 0  0  9]]

🔹 Decision Tree Visualization

Each node shows:

Splitting feature and threshold

Gini / Entropy impurity

Number of samples per class

Predicted class

This visualization helps understand how decisions are made by the model.
