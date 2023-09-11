# DataMining2-Human_Activity_Recognition
 Project for the exam of Data Mining - Part II Advanced Topics. Dataset available in (https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones)



## Project Task 1 
#### Data Understanding and Preparation
1. Explore and prepare the dataset. You are allowed to take inspiration 
from existing notebooks you can find online and figure out your 
personal research perspective (from choosing a subset of variables to 
the class to predict…). You are welcome in creating new variables and 
performing all the pre-processing steps the dataset needs.
#### Outliers
1. - Identify the top 1% outliers: adopt at least three different methods 
from different families (e.g., density-based, angle-based…) and 
compare the results. 
2. Visualize the outliers in a 2 or 3d scatter plot using at least one 
dimensionality reduction technique.
3. Deal with the outliers in a way you see fit, e.g. by removing them from 
the dataset or by treating the anomalous variables as missing values 
and employing replacement techniques. In this second case, you 
should check that the outliers are not outliers anymore. Justify your 
choices in every step.
#### Imbalanced Learning
1. Define one simple unbalanced classification tasks and solve it with 
Decision Tree or KNN. 
2. If the dataset is already unbalanced leave it as it is, otherwise turns 
the dataset into an imbalanced version (e.g., 96% - 4%, for binary 
classification). 
3. Then solve the classification task using the Decision Tree or KNN by 
adopting at least 2 techniques of imbalanced learning (Undersampling, 
Oversampling).

## Project Task 2
#### Advanced Classification

1. Solve the classification task defined in Module 1 (or define new ones) with the 
other classification methods analyzed during the course: Logistic Regression, 
Support Vector Machines, Neural Networks, Ensemble Methods, Gradient Boosting 
Machines.
2. Always perform hyper-parameter tuning phases and justify your choices (which are the best parameters? which parameters did you test and why?).
- Evaluate each classifier with the techniques presented in DM1: accuracy (or 
precision, recall, F1-score etc), ROC curve (or lift, precision-recall etc). 
3. Besides the numerical evaluation draw your conclusions about the various 
classifiers (e.g. for Neural Networks: what are the parameter sets or the 
convergence criteria which avoid overfitting? For Ensemble classifiers how the 
number of base models impact the classification performance? What is revealing 
the feature importance of Random Forests?)

#### Advanced Regression

1. Define a multiple regression task, i.e., using more than one input 
feature, and solve it using 2 advanced regression approaches (not 
linear).
2. Compare and evaluate the approaches using appropriate metrics.

## Project Task 3
#### Data Understanding and Preparation

1. Explore and prepare the time series dataset.
2. Preprocess the dataset in order to be able to run time series 
clustering; motif/anomaly discovery and classification. If the dataset is 
too big for these tasks, you can use approximations (e.g. SAX, PAA etc)

#### Motifs/Discords
1. Analyze the dataset for finding motifs and/or anomalies. Visualize and 
discuss them and their relationship with shapelets.

#### Clustering

1. Use at least two clustering algorithm on time series using an 
appropriate distance.
2. Analyze the clusters and highlight similarities and differences and 
visualize the clusters using at least 2 dimensionality reduction 
techniques.


#### Classification
1. Define one (or more) classification task and solve it using:
 - KNN with at least two distances
 - Euclidean/Manhattan 
 - DTW 
 - Shapelets
 - Analyze the shapelets retrieved
 - At least one other method (rocket, muse, cnn, rnn etc)

## Project Task 4
#### Explainability
1. Try to use one or more explanation methods (e.g., TREPAN, LIME, 
LORE, SHAP, Counterfactual Explainers, etc.) to illustrate the reasons for 
the classification in one of the steps of the previous tasks.





