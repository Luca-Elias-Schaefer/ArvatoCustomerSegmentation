# Arvato Customer Segmentation
In this project, we create a customer segmentation report for Arvato Financial Solutions. The project is divided into three main parts:
- Data preprocessing
- Unsupervised learning to create customer segments
- Supervised learning to predict which individuals are most likely to respond to a marketing campaign

## Libraries
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns

- from sklearn.preprocessing import MinMaxScaler
- from sklearn.decomposition import PCA
- from sklearn.cluster import MiniBatchKMeans
- from sklearn.cluster import KMeans
- from sklearn.model_selection import train_test_split
- from sklearn.model_selection import GridSearchCV
- from sklearn.metrics import plot_roc_curve
- from sklearn.metrics import roc_auc_score
- from sklearn.feature_selection import SelectKBest, f_classif
- from sklearn.linear_model import LogisticRegression
- from sklearn.ensemble import RandomForestClassifier
- from sklearn.neighbors import KNeighborsClassifier
- from sklearn.ensemble import AdaBoostClassifier
- from sklearn.tree import DecisionTreeClassifier
- from sklearn.discriminant_analysis import QuadraticDiscriminantAnalysis
- from sklearn.neural_network import MLPClassifier
- from sklearn.ensemble import GradientBoostingClassifier

## Datasets
The datasets were provided by Arvato Finacial Solutions.

- Udacity_AZDIAS_052018.csv
- Udacity_CUSTOMERS_052018.csv
- Udacity_MAILOUT_052018_TRAIN.csv
- Udacity_MAILOUT_052018_TEST.csv
- DIAS Information Levels - Attributes 2017.xlsx
- DIAS Attributes - Values 2017.xlsx

Whereas the first four datasets were used for building the models, the last two datasets provided a high-level description of the above-mentioned datasets.
