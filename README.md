# IrisSVMClassifier

Welcome to my Support Vector Machine Project! We will be analyzing the famous iris data set.

## Project Description

In this project, we will use Support Vector Machines (SVMs) to classify iris flowers into three species based on their sepal and petal measurements. The dataset we are using is the famous [Iris flower data set](http://en.wikipedia.org/wiki/Iris_flower_data_set), introduced by Sir Ronald Fisher in 1936.

## The Data

The Iris flower data set consists of 150 samples from three species of Iris flowers:
- Iris setosa
- Iris versicolor
- Iris virginica

For each sample, the following four features were measured:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## Methodology

### 1. Importing Libraries

First, we import the necessary libraries required for data manipulation, visualization, and building the SVM model.

### 2. Loading the Dataset

We load the Iris dataset using scikit-learn's built-in datasets module.

### 3. Exploratory Data Analysis (EDA)

We perform EDA to understand the dataset better. This involves visualizing the distribution of features and exploring relationships between them.

### 4. Preparing the Data

We preprocess the data by splitting it into training and testing sets. We also scale the features to ensure they have a similar range.

### 5. Building a Support Vector Machine Model

We build and train an SVM model using scikit-learn. SVMs will be used to classify iris flowers into their respective species based on the features provided.

### 6. Evaluating the Model

We evaluate the performance of the SVM model using accuracy score and confusion matrix. This helps us understand how well the model is performing and whether adjustments are needed.

## Conclusion

This project demonstrates the application of Support Vector Machines for multiclass classification using the Iris flower dataset. It covers data loading, preprocessing, model building, and evaluation, providing a practical introduction to SVMs in machine learning.

## Usage

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook file `iris_svm_classifier.ipynb`.
3. Follow the steps in the notebook to load the dataset, preprocess the data, build and train the SVM model, and evaluate its performance.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- The [Iris flower data set](http://en.wikipedia.org/wiki/Iris_flower_data_set) for providing the dataset.
- Scikit-learn and other open-source libraries for their contributions to machine learning and data analysis.
