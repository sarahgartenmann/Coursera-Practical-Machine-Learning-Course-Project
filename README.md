# Coursera-Practical-Machine-Learning-Course-Project

This is the course project for the Practical Machine Learning Course on Coursera. Data used in this project is from the Human Activity Recognition project from Groupware@LES.

In this project, we will use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants to predict the manner in which they did the exercise. This is the “classe” variable in the training set. We train 4 models: Decision Tree, Random Forest, Gradient Boosted Trees, Support Vector Machine using k-folds cross validation on the training set. We then predict using a validation set randomly selected from the training csv data to obtain the accuracy and out of sample error rate. Based on those numbers, we decide on the best model, and use it to predict 20 cases using the test csv set.

Files: 
202301_Coursera_PracticalMachineLearning_CourseProject.Rmd is the r-markdown 
202301_Coursera_PracticalMachineLearning_CourseProject.html is the html output
