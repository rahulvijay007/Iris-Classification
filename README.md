Iris Flower Classification
This repository contains a machine learning project for classifying iris flowers into three species using various classification algorithms such as Support Vector Machine (SVM), Random Forest, K-Nearest Neighbors (KNN), and a Neural Network implemented in TensorFlow.

Dataset
The dataset used in this project is the famous Iris dataset, which consists of 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The target variable is the species of iris, which can be one of three classes: setosa, versicolor, or virginica.

Data Exploration
Exploratory Data Analysis (EDA) was performed on the dataset to visualize the relationships between features and species classes using pair plots and box plots.

Model Building and Evaluation
Support Vector Machine (SVM)
A linear Support Vector Machine (SVM) classifier was trained on the scaled features of the dataset. 

Random Forest
A Random Forest classifier with 100 trees was trained on the scaled features. 

K-Nearest Neighbors (KNN)
A K-Nearest Neighbors classifier with k=3 was trained on the scaled features. 

Neural Network (TensorFlow)
A simple Neural Network with two hidden layers was implemented using TensorFlow. 

Model Evaluation
Each trained model was evaluated using metrics such as accuracy, classification report, and confusion matrix. The results were visualized using seaborn and matplotlib.

Predictions
An example prediction was made using the trained Support Vector Machine (SVM) model on a sample input [5.1, 3.5, 1.4, 0.2], resulting in the prediction of the class [Iris-setosa].
