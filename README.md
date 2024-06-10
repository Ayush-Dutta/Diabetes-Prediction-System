# Diabetes Prediction Model using SVM Classifier

This repository hosts a machine learning model capable of predicting diabetes based on various health parameters. The model utilizes a Support Vector Machine (SVM) classifier, a powerful algorithm for classification tasks. 

## About the Dataset

The dataset used to train the model contains a collection of health-related data points for individuals, sourced from Kaggle. It includes attributes such as glucose levels, blood pressure, skin thickness, insulin levels, BMI, age, and more. Each entry in the dataset is labeled as either diabetic or non-diabetic.

## How it Works

The model is trained to recognize patterns in the provided health data and correlate them with the presence or absence of diabetes. It learns from the dataset to make predictions on new, unseen data. By leveraging SVM, the model is able to construct a hyperplane that effectively separates the data into diabetic and non-diabetic classes.

## Usage

To use the model, simply follow these steps:

1. **Clone the Repository**: Download or clone this repository to your local machine.

2. **Run the Script**: Execute the `diabetes_prediction_svm.py` script. This script loads the dataset, preprocesses the data, trains the SVM classifier, evaluates its performance, and provides a predictive system to make real-time predictions.

3. **Interpret the Results**: After running the script, you'll see the accuracy of the model on both training and testing data. You can also input new health parameters to see if the model predicts the individual as diabetic or non-diabetic.

## Predictive System

One of the key features of this model is its predictive system. You can input a set of health parameters into the script, and the model will output whether the individual is likely to be diabetic or not. This functionality can be useful for healthcare professionals and individuals alike in assessing diabetes risk.

## Contribution

Contributions to this project are welcome! Whether it's improving the model's accuracy, adding new features, or enhancing the documentation, feel free to submit a pull request.


## Acknowledgments

- Kaggle for providing the dataset.
- Scikit-learn for the SVM implementation.
- Open-source community for valuable contributions and feedback.
