# Support Vector Machine (SVM) Classification Project

## Introduction
This project implements a Support Vector Machine (SVM) for classification, utilizing a synthetic dataset generated via scikit-learn's blob generator. SVMs are powerful algorithms used for both regression and classification tasks, but they are most widely recognized for their effectiveness in classification. The primary objective of an SVM algorithm is to identify a hyperplane in N-dimensional space that distinctly classifies data points with maximum margin.

## Dataset

The dataset for this project is synthetically generated using the following scikit-learn command:


```python
from sklearn.datasets import make_classification

X, y = make_classification(n_samples=500, n_features=3, n_informative=3, n_redundant=0, n_clusters_per_class=1, flip_y=0.1, class_sep=1.0, random_state=40)
```

This command generates a dataset with 500 samples, 3 features, and binary targets relabeled to +1 and -1 to fit the SVM algorithm requirements.

## Requirements

To successfully execute this project, the following steps are implemented:

1. Relabel the Y targets to +1/-1.
2. Split the dataset into training and testing datasets.
3. Implement soft margin SVM.
4. Use mini batch gradient descent to minimize the loss function.
5. Return the optimal weights by minimizing the loss function.
6. Perform predictions on the test data.
7. Calculate the accuracy score.
8. Visualize the training data and decision boundary in 3D.
9. Visualize the loss function over time during training.

## Deliverables

- A working project contained in a Python Notebook (.ipynb) or Python script (.py).
- Detailed comments about the source code are embedded within markup cells (for notebooks) or comments (for scripts).

## Instructions on How to Run This Project

1. Ensure you have Python 3.x installed along with the following packages: `scikit-learn`, `numpy`, `matplotlib`.
2. Clone this repository to your local machine.
3. Open the terminal (or command prompt) and navigate to the project directory.
4. Run the project using Jupyter Notebook or directly as a Python script:
   - For Jupyter Notebook: `jupyter notebook SVM_Classification_Project.ipynb`
   - For Python script: `python SVM_Classification_Project.py`

## Notes

- It's essential to test the program with the provided dataset before submission.
- Discussions with peers on general concepts are encouraged, but the implementation should be individual work. Sharing code or reports is strictly prohibited and may result in a grade penalty.
- Late submissions will be penalized at a rate of 10 points per day past the deadline.
