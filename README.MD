# Disease Prediction with Machine Learning

This code implements a machine learning model to predict diseases based on symptoms. The dataset is available at <https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning>.

## Getting Started

### Prerequisites

To run the code, you will need to install the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn

You can install the required packages using the requirements.txt file provided in this repository. To install the dependencies, run the following command:

```pip install -r requirements.txt```

### Dataset

The dataset "Training.csv" and "Testing.csv" should be placed in the "data" directory within the repository.

## Models

The script trains three different machine learning models on the preprocessed data:

1. Gaussian Naive Bayes
2. Random Forest Classifier
3. Support Vector Classifier (SVC) with RBF kernel

implements a function that can take symptoms as input and generate predictions for disease based on the combined prediction of the 3 models.
