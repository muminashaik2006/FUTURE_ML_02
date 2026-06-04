# Customer Support Ticket Classification

## Overview

This project uses Machine Learning and Natural Language Processing (NLP) to automatically classify customer support tickets into different categories based on their ticket descriptions and subjects.

The system helps organizations route customer issues efficiently, reduce manual effort, and improve response times.

## Features

* Text preprocessing and cleaning
* TF-IDF feature extraction
* Support ticket classification using Linear Support Vector Machine (Linear SVC)
* Model evaluation using accuracy score
* Confusion Matrix visualization
* Organized project structure for deployment and future enhancements

## Dataset

The dataset contains customer support tickets with the following fields:

* Ticket Description
* Ticket Subject
* Ticket Type
* Ticket Priority

Source: Customer Support Tickets Dataset

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib


## Workflow

1. Load customer support ticket dataset.
2. Select relevant text columns.
3. Combine ticket description and subject.
4. Convert text into numerical features using TF-IDF.
5. Split dataset into training and testing sets.
6. Train Linear SVC classifier.
7. Evaluate model performance.
8. Visualize results using confusion matrix.

## Model

Algorithm Used:

* Linear Support Vector Classifier (LinearSVC)

Why LinearSVC?

* Efficient for text classification tasks
* Works well with high-dimensional TF-IDF features
* Fast training and prediction

## Results

The model predicts customer ticket categories based on textual information and provides classification accuracy along with a confusion matrix visualization.

## Future Improvements

* Hyperparameter tuning
* Deep Learning models (LSTM, BERT)
* Web application deployment using Flask or Streamlit
* Real-time ticket classification API

## Author

SHAIK MUMINA

