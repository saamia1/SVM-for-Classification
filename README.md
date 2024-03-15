# Support Vector Machine (SVM) Classification Project

## Introduction
This project implements a Support Vector Machine (SVM) for classification, utilizing a synthetic dataset generated via scikit-learn's blob generator. SVMs are powerful algorithms used for both regression and classification tasks, but they are most widely recognized for their effectiveness in classification. The primary objective of an SVM algorithm is to identify a hyperplane in N-dimensional space that distinctly classifies data points with maximum margin.

## Dataset

The dataset for this project is synthetically generated using the following scikit-learn command:


```python
from sklearn.datasets import make_classification

X, y = make_classification(n_samples=500, n_features=3, n_informative=3, n_redundant=0, n_clusters_per_class=1, flip_y=0.1, class_sep=1.0, random_state=40)
```

