This project uses machine learning to classify vegetables into categories — leafy, root, or fruit — based on their nutritional values: Vitamin A, Vitamin C, and Fiber.

 Problem Statement
The goal is to build a model that can automatically classify vegetables by analyzing their nutritional content. This can be helpful for:

Nutritional planning

Diet tracking apps

Smart farming tools

 Machine Learning Approach
We use the Random Forest Classifier — an ensemble learning method that combines multiple decision trees for better accuracy and robustness.

 Tools & Libraries
Python

pandas – data manipulation

scikit-learn – model building and evaluation

seaborn & matplotlib – visualization

 Dataset
The dataset contains columns:

vitamin_a — Amount of Vitamin A

vitamin_c — Amount of Vitamin C

fiber — Fiber content

type — Target label (Leafy, Root, Fruit)

 File: vegetables.csv

 Steps Performed
Load and explore the dataset

Preprocess data (label encoding, train-test split)

Train Random Forest Classifier

Evaluate the model (Accuracy, Precision, Recall, F1-score)

Visualize the confusion matrix using a heatmap

 Results
High accuracy and balanced performance across classes

Clean classification report

Heatmap of confusion matrix for visual analysis
