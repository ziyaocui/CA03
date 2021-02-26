## Name of project
Decision Tree Algorithm

## Project Overview 
The data Census Bureau and represents salaries of people along with seven demographic variables. Set data into different categories and use train data to build a model for test data. Finally purpose is to find the best model and decision tree.

## Instruction
Please use the census data to run the code in Google Colab

## Installation instructions
Use the following packages:

```bash
pandas
numpy
os
matplotlib pyplot
sklearn.metrics
```
## Usage 
```python
import pandas as pd
import os
import numpy as np
import matplotlib.pyplot as plt
from sklearn.tree import export_graphviz
from sklearn.externals.six import StringIO  
from IPython.display import Image  
import pydotplus
from sklearn.metrics import classification_report, confusion_matrix
from sklearn.metrics import roc_curve
from sklearn.metrics import auc
from sklearn.metrics import roc_auc_score
from sklearn.metrics import accuracy_score
from sklearn.metrics import precision_score
from sklearn.metrics import f1_score
from sklearn.metrics import recall_score
```

## Operating instructions
1. First step is to improt all packages that will use later.
2. Next step is to find missing values in the data and clean the data.
3. Next part is to plot income vs. other seven different variables. 
4. Build decision model and calculate four different scores for each model.

## Conclusion
Choosing the best model using Entropy, final accuracy score is 84.4%.

## Colab access
https://colab.research.google.com/drive/19mrskXGXDkMLkEssAgTmZ7cW1fUPZ0CQ?usp=sharing

## Data

"census_data.csv"

## Contact information
Name: Ziyao Cui
