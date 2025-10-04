# RANDOM FOREST CLASSIFICATION WITH PYTHON AND SCI-KIT LEARNING

Random Forest is a Machine Learning Algorithm that combines multiple Decision Trees. In this project i build two models based on random forest to predict the safety / 
how healthy the food is based upon it's nutritional values, its various types based upon regional variations, etc. 
I build one model with 11 Decision Trees and the other one with 100 Decision Trees

## 1. Introduction to Random Forest

Random Forest is a supervised learning algorithm used for classification and regression. It builds multiple decision trees, combines their predictions, and chooses the most voted outcome (counted from the outcome of each decision tree)
. It is flexible, accurate, and can show which features are most important. More trees usually lead to better accuracy.
## 2. How It Works

Randomly select a subset of features.

Build multiple decision trees using random splits.

Make predictions with all trees and choose the majority vote as the final prediction.

## 3. Pros and Cons

Advantages:

Works for both classification and regression.

Can handle missing data.

Useful for feature importance and selection.

Disadvantages:

Computationally heavy with many trees.

Harder to work with than a single decision tree.

Model often memorize the data instead of the pattern

## 4. Feature Selection

Random Forest can rank feature importance by measuring how each feature affects prediction accuracy. Features with high importance are used for better model building; low-impact features can be dropped.

## 5. Random Forest vs Decision Trees

Random Forest = multiple trees; Decision Tree = single tree.

Random Forest prevents overfitting better.

Decision Trees are faster and easier to interpret.

## 6. Problem Statement

Predict car safety using the Car Evaluation Dataset from UCI:
Dataset Link

## 7. Results
From my project

Model with 11 trees = 89.16% accuracy

Model with 100 trees = 90.36% accuracy

Feature analysis showed doors had minimal effect; removing it slightly improved accuracy.

Confusion matrix and classification report confirm model performance.

## 8. Applications

Random Forest can be applied to:

Recommendation engines

Image classification

Feature selection


  

