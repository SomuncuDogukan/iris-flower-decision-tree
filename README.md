# Iris Flower Classification using Decision Tree

This project implements a classification model using a Decision Tree algorithm to predict the species of iris flowers. The model is trained on the Iris flower dataset, which contains numerical measurements of sepal and petal dimensions for three species: Setosa, Versicolor, and Virginica.

Note: "Iris" in this context refers to a flower genus, not the human eye.

## Dataset

- Source: `sklearn.datasets.load_iris()`
- Features:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- Classes:
  - 0 = Setosa
  - 1 = Versicolor
  - 2 = Virginica
- Total samples: 150

## Project Workflow

1. Load and explore the dataset
2. Split into training and test sets (80% / 20%)
3. Train a Decision Tree classifier using the Gini index
4. Evaluate performance using:
   - Accuracy score
   - Confusion matrix
5. Visualize the trained decision tree
6. Analyze feature importance

## Decision Tree Visualization

The diagram below shows the trained tree structure. Nodes contain:
- Gini impurity
- Number of samples
- Class distribution
- Predicted class


<img width="1000" height="500" alt="Figure_1" src="https://github.com/user-attachments/assets/0863f34e-3de4-441f-820a-1e2de5670c2a" />


