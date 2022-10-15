# CS4372 Assignment 2

The following project was made using Jupyter Notebook. It used the auto_mpg.csv data and had to be cleaned.

## Models 

1. Plain Decision Tree Classifier 
2. Random Forest Classifier 
3. Adaboot Classifier 
4. XGBoost Classifier 

## Encoding and 80/20 split

I had to encode my y_train values for XGBoost. I changed “Asia”, “Europe” and “US” to “0”,”1”, “2” respectively. I split the data to fit the 80-20 model wherein 80% went to training dataset (x_train and y_train) and 20% went to testing datasets (x_test and y_tests).  Five models were built:
1. Decision Tree
2. Random Forrest
3. Random Forrest with parameter tuning
4. AdaBoost with parameter tuning
5. XGBoost with parameter tuning

![Screenshot 2022-10-15 at 00-56-13 decision_tree_picture pdf](https://user-images.githubusercontent.com/8845450/195972252-57b2e2da-fa6b-448e-8b4a-e813666ea00d.png)

## Packages used in Jupyter Notebook

python 3.6
graphviz              0.20.1
matplotlib            3.5.3
numpy                 1.23.2
pandas                1.4.4
scikit-learn          1.1.2
scikit-plot           0.3.7
scipy                 1.9.1
seaborn               0.12.0
xgboost               1.6.2
