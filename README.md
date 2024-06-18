# CodeAlpha_Disease-Prediction-Model

This repository contains Python code for classifying breast cancer tumors as malignant or benign using various machine learning algorithms and techniques.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- mlxtend

## Data

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Dataset from the UCI Machine Learning Repository. It contains features computed from digitized images of a fine needle aspirate (FNA) of a breast mass. The features describe characteristics of the cell nuclei present in the image.

## Code Overview

The code performs the following tasks:

1. Imports necessary libraries and modules.
2. Loads the breast cancer dataset.
3. Splits the dataset into training and testing sets.
4. Performs feature selection using the SelectKBest method.
5. Scales the feature values using MinMaxScaler.
6. Trains and evaluates various classification models:
   - Random Forest Classifier
   - K-Nearest Neighbors Classifier
7. Optimizes hyperparameters of the models using RandomizedSearchCV and GridSearchCV.
8. Computes and prints classification metrics (accuracy, precision, recall, F1-score) for each model.
9. Plots confusion matrices for the models.

## Usage

1. Clone the repository or download the code files.
2. Install the required libraries and modules.
3. Run the Python script.
4. The script will execute the code and print the classification metrics and confusion matrices for each model.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
