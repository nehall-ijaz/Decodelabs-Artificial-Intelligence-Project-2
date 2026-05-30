# Decodelabs-Artificial-Intelligence-Project-2
# Project 2: Data Classification Using AI

## Submitted By:

Name: Nehall Ijaz

Batch: 2026

## Objective

The objective of this project is to build a basic classification model using Artificial Intelligence. The model learns from a dataset and predicts the category of new data. This project introduces the concepts of supervised learning, data preprocessing, model training, and evaluation.

## Tools and Libraries Used

* Python
* Scikit-learn
* NumPy
* Pandas

## Dataset

The Iris dataset was used for this project. It contains measurements of iris flowers, including:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The dataset has three flower classes:

1. Setosa
2. Versicolor
3. Virginica

## Methodology

### Step 1: Load Dataset

The Iris dataset was loaded using Scikit-learn.

### Step 2: Split Dataset

The dataset was divided into:

* Training Data (80%)
* Testing Data (20%)

### Step 3: Feature Scaling

StandardScaler was applied to normalize the data and improve model performance.

### Step 4: Model Training

A K-Nearest Neighbors (KNN) classifier with K=5 was used to train the model.

### Step 5: Prediction

The trained model was used to predict flower classes for unseen data.

### Step 6: Evaluation

The model performance was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

## Results

The KNN classification model successfully classified iris flowers with high accuracy. The confusion matrix and classification report showed that the model performed well on the testing dataset.

## Conclusion

This project demonstrated the complete workflow of a supervised machine learning classification task. The Iris dataset was successfully classified using the K-Nearest Neighbors algorithm. The project provided practical experience in data preprocessing, model training, testing, and evaluation, which are essential skills in Artificial Intelligence and Machine Learning.

## Future Improvements

* Test different classification algorithms.
* Increase dataset size.
* Perform hyperparameter tuning.
* Compare model performances for better accuracy.
