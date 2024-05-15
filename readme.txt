For this project, I have used Google Collab for the implementation of code.
Below are the libraries that I have used and imported.

NUMPY: This Package is used to run the mathematical operations.
command:import numpy as np

PANDAS: Pandas library is used for data analysis
command: import pandas as pd

tRAIN_TEST_SPLIT  FROM SKLEARN: This package is used to train and test the data
command: from sklearn.model_selection import train_test_split

from sklearn.ensemble import RandomForestClassifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import confusion_matrix, accuracy_score, precision_score, recall_score, f1_score

The above packages are imported to calculate the confusion_matrix, accuracy_score, precision_score, recall_score, and f1_score for 3 classifiers. 

First, the given data needs to be split and where 75% is used to train the data, and the rest of the data (25%) is used for testing. Then, simulation parameters are initialized for each of these classifiers. Each of the classifier's performance. 