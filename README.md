
# Iris Classification using Multiple Machine Learning Algorithms

This project demonstrates the classification of the Iris dataset using four different machine learning algorithms: Random Forest, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Logistic Regression.

## Introduction

The Iris dataset is a classic dataset in the field of machine learning and statistics. It contains 150 observations of iris flowers with four features each: sepal length, sepal width, petal length, and petal width. The goal is to classify the flowers into one of three species: Setosa, Versicolor, or Virginica.

This project implements four different machine learning algorithms to classify the Iris dataset and compares their performance.

## Dataset

The Iris dataset is available in the UCI Machine Learning Repository and is included in many machine learning libraries, including scikit-learn.

- **Number of instances**: 150
- **Number of attributes**: 4 numeric, predictive attributes and the class
- **Attribute information**:
  1. sepal length in cm
  2. sepal width in cm
  3. petal length in cm
  4. petal width in cm
  5. class:
     - Iris Setosa
     - Iris Versicolour
     - Iris Virginica

## Installation

To run this project, you need to have Python installed along with the following libraries:

- numpy
- pandas
- scikit-learn
- matplotlib (optional, for visualization)

You can install these dependencies using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Iris_Flower_Classification.git
    cd Iris_Flower_Classification
    ```

2. Run the classification script:
    ```bash
    python Iris_Flower_Classification.py
    ```

The script will load the Iris dataset, train the models, and display the accuracy of each algorithm.

## Algorithms

### Random Forest

Random Forest is an ensemble method that fits multiple decision trees on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting.

### K-Nearest Neighbors (KNN)

KNN is a simple, instance-based learning algorithm. It classifies a sample based on the majority class among the k-nearest neighbors of the sample in the feature space.

### Support Vector Machine (SVM)

SVM is a powerful classifier that works by finding the hyperplane that best separates the classes in the feature space. It is effective in high-dimensional spaces and when the number of dimensions is greater than the number of samples.

### Logistic Regression

Logistic Regression is a linear model for binary classification that can be extended to multiclass problems. It uses the logistic function to model the probability of the default class.

## Results

The performance of each algorithm is evaluated using accuracy, which is the proportion of correctly classified instances out of the total instances. Here are the accuracies of each algorithm on the Iris dataset:

- **Random Forest**: 95.55%
- **K-Nearest Neighbors (KNN)**: 100%
- **Support Vector Machine (SVM)**: 97.77%
- **Logistic Regression**: 95.55%

## Conclusion

All four algorithms perform well on the Iris dataset, but their performance may vary depending on the specific characteristics of the dataset and the parameters used for each model. Random Forest and SVM generally perform very well due to their robustness and ability to handle complex relationships in the data.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
.
