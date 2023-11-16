# Supervised Learning Project: Comparing Classification Models

## Overview
This project compares and contrasts the performance of three different supervised learning models on the famous iris flowers dataset. The goal is to predict the species of iris flowers based on their measurements using the following three learning models:
- Logistic Regression (LR)
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## Dependencies
Make sure the following Python libraries are installed before running the code:
- scipy
- numpy
- matplotlib
- pandas
- scikit-learn

To check if the required libraries are installed, run the following code in a Python environment:
```python
import sys
import scipy
import numpy
import matplotlib
import pandas
import sklearn

print('Python: {}'.format(sys.version))
print('scipy: {}'.format(scipy.__version__))
print('numpy: {}'.format(numpy.__version__))
print('matplotlib: {}'.format(matplotlib.__version__))
print('pandas: {}'.format(pandas.__version__))
print('sklearn: {}'.format(sklearn.__version__))
```

## Code Details
The code includes the necessary Python script to perform supervised learning, specifically classification, on the iris flowers dataset. It covers the following key steps:

1. Importing libraries
2. Loading the dataset
3. Dataset properties, including shape, head, descriptions, and class distribution
4. Data visualizations, such as histograms and scatter plot matrix
5. Model evaluation through the creation of a validation dataset, 10-fold cross-validation, and model building
6. Making predictions on the validation dataset and evaluating model performance

## Usage
To run this project:
1. Clone this repository to your local machine.
2. Navigate to the cloned directory and execute the provided Python script.

```bash
python compare_classification_models.py
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


