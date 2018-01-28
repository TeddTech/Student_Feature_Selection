# Student_Feature_Selection

This projects uses the [Student Performance Data Set](http://archive.ics.uci.edu/ml/datasets/Student+Performance) from the UCI machine learning repository. The objective of the project is to build a model and select features from the data set that can best predict whether or not I student passed or failed a course.

There are two data sets provided in the `data` folder one for a set of students studied in math class another for that same set of students studied in Portuguese class. The source code provided for this analysis was create for the math data set but can also be run on the Portuguese data set. To run the analysis open jupyter notebook and select the `Student_Feature_Selection.ipynb` file and toggle through the file running each code block.

Usage:

```
jupyter notebook
```

Usage example:

```
jupyter notebook
```

Dependencies:

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.model_selection import GridSearchCV
from sklearn.model_selection import ShuffleSplit
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.svm import LinearSVC
from sklearn.svm import SVC
from itertools import chain
```


## by Ted Thompson

### 2018
