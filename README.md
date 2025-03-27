# Iris Classification using Random Forest

## Overview

This project implements a *Random Forest Classifier* to classify the *Iris dataset* into different species. It includes data preprocessing, model training, evaluation, and visualization of feature importance and performance metrics.

## Dataset

The dataset used is the *Iris dataset*, which contains 150 samples of iris flowers with the following features:

- sepal_length
- sepal_width
- petal_length
- petal_width
- species (Target variable: Setosa, Versicolor, Virginica)

## Installation

### Prerequisites

Ensure you have *Python 3.7+* installed and the required libraries:

bash
pip install pandas numpy seaborn scikit-learn matplotlib


## Usage

### 1. Clone the repository

bash
git clone https://github.com/your-username/iris-classification.git
cd iris-classification


### 2. Run the script

bash
python iris_classification.py


## Implementation Details

- Loads the *Iris dataset* from IRIS.csv
- Encodes species labels into numerical values
- Splits the data into *training (80%)* and *testing (20%)* sets
- Trains a *Random Forest Classifier* with 100 estimators
- Evaluates the model using *accuracy, confusion matrix, and classification report*
- Visualizes the *feature importance and confusion matrix*

## Output

- *Model Accuracy*
- *Feature Importance Ranking*
- *Confusion Matrix Heatmap*
- *Classification Report*

## Results

The model achieves *high accuracy* on the test set, indicating effective classification.

## Contributing

Contributions are welcome! Feel free to:

- Open an issue for bugs or feature requests
- Submit a pull request with improvements

## License

This project is licensed under the *MIT License*.

## Author

SRIPATHI RAO KARRI
