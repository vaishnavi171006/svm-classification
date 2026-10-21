# svm-classification
Support Vector Machine (SVM) classification using Python and Scikit-learn with the Iris dataset, feature scaling, model evaluation, and RBF kernel.
# Support Vector Machine (SVM) for Classification

## 📌 Project Overview
This project demonstrates the implementation of the Support Vector Machine (SVM) algorithm for classification using Python and Scikit-learn. The model uses the Iris dataset to classify flowers into different species based on their physical measurements.

## 🎯 Aim
To practically implement and understand the fundamental concepts of Support Vector Machine (SVM), a supervised machine learning algorithm used for classification, through coding and data analysis.

## 🎯 Objectives
- Understand the theoretical foundation of SVM.
- Learn how hyperplanes and support vectors work.
- Implement SVM using Python and Scikit-learn.
- Preprocess data and perform feature scaling.
- Train an SVM classifier and evaluate its performance.
- Understand linear and non-linear kernel functions.

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

## 📂 Project Structure

```text
svm-classification/
│
├── svm_classification.ipynb
└── README.md
```

## 📚 Theory

### What is Support Vector Machine?
Support Vector Machine (SVM) is a supervised machine learning algorithm mainly used for classification tasks. It identifies an optimal decision boundary, called a hyperplane, that separates data points belonging to different classes.

### Key Concepts

- **Hyperplane:** A decision boundary that separates different classes.
- **Support Vectors:** Data points closest to the hyperplane that influence its position.
- **Margin:** The distance between the decision boundary and the nearest data points. SVM aims to maximize this margin.
- **Kernel:** A function that helps SVM classify data that cannot be separated using a straight line.
- **Regularization Parameter (C):** Controls the trade-off between maximizing the margin and penalizing classification errors.

### Hyperplane Equation

w · x + b = 0

Where:
- `w` represents the weight vector.
- `x` represents the input feature vector.
- `b` represents the bias term.

### Types of SVM

1. **Linear SVM:** Used when classes can be separated approximately by a linear decision boundary.
2. **Non-Linear SVM:** Uses kernel functions to classify data that cannot be separated by a linear boundary.

### Common Kernel Functions
- Linear Kernel
- Polynomial Kernel
- Radial Basis Function (RBF) Kernel
- Sigmoid Kernel

This project uses the RBF kernel to classify flower species.

## 📊 Dataset
The project uses the Iris dataset, which contains measurements of flowers belonging to three species:

- Setosa
- Versicolor
- Virginica

The input features are:
- Sepal length
- Sepal width
- Petal length
- Petal width

The target variable is `species`.

## ⚙️ Algorithm Steps
1. Import the required Python libraries.
2. Load the Iris dataset.
3. Display the first five rows of the dataset.
4. Check for missing values.
5. Separate input features and target labels.
6. Split the dataset into training and testing sets.
7. Standardize the input features using StandardScaler.
8. Create and train the SVM classifier using the RBF kernel.
9. Predict flower species using the test data.
10. Evaluate the model using accuracy, confusion matrix, and classification report.
11. Predict the species of a new flower sample.

## 🚀 How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries if they are not already installed:

   ```bash
   pip install pandas numpy scikit-learn jupyter
   ```

3. Open Jupyter Notebook.
4. Open `svm_classification.ipynb`.
5. Run the notebook cells sequentially.
6. Observe the model's predictions and evaluation results.

**Note:** The notebook downloads the Iris dataset from an online CSV source, so an internet connection is required when using that version of the code.

## 📈 Model Evaluation
The classifier is evaluated using the following metrics:

- **Accuracy:** Measures the proportion of correct predictions.
- **Confusion Matrix:** Shows correct and incorrect predictions for each class.
- **Precision:** Measures the correctness of positive predictions for each class.
- **Recall:** Measures how many actual instances of each class are correctly identified.
- **F1-score:** Provides a balance between precision and recall.

## 🔍 Expected Output
- First five rows of the Iris dataset.
- Missing-value information.
- Model accuracy percentage.
- Confusion matrix.
- Classification report.
- Predicted species for a new flower sample.

## 📚 Learning Outcomes
- Understand the working principle of SVM.
- Learn about hyperplanes, support vectors, and margins.
- Perform feature scaling before training a model.
- Implement an SVM classifier using Scikit-learn.
- Evaluate a classification model using multiple metrics.
- Understand the role of kernel functions in classification.
