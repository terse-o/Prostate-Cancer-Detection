Prostate Cancer Detection

Language: R
Editor: RStudio (v1.2.1335)
Description: Implemented kNN algorithm from 2 different packages to classify whether the prostate cancer in the patient is benign or malignant.

NOTE: As part of my graduate program, I created small projects like this to get a better understanding of AI and ML algortihms.

Link for dataset: https://drive.google.com/file/d/1MtjBKmDHFVG5PgKJg-9V3HYvuCwsehIC/view?usp=sharing

Packages: class, gmodels, ISLR, caret, lattice, ggplot2, e1071
Model: kNN

OVERVIEW:
-Load data
-Normalize
-Split into train and test sets
-Apply kNN algorithm from class package on training set
-Apply kNN algorithm from caret package on training set
-Use trained model to predict known values from test set
-Create confusion matrix to evaluate the 2 models