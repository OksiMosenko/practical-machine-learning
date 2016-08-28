# Practical Machine Learning
Coursera's Data Science Specialization, Practical Machine Learning project, Week 4


##Background

Using devices such as JawboneUp, NikeFuelBand, and Fitbitit is now possible to collect a large amount of data about personal 
activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who 
take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech 
geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well 
they do it.

In this project, the goal is to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. 
They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from 
the website (see the section on the Weight Lifting Exercise Dataset).

##Data

The training data for this project are available here. The test data are available here.

The data for this project come from this source. If you use the document you create for this class for any purpose please cite them as they have been very generous in allowing their data to be used for this kind of assignment.


##Project's rubric

The goal of the project is to predict the manner in which they did the exercise. This is the classe variable in the training set. Use any of the other variables to predict with.

Create a report describing how to build the model, how to use cross validation, what the expected out of sample error is, and why make the choices. Then use the prediction model to predict 20 different test cases.

The submission should consist of a link to (this) Github repo with the R markdown and compiled HTML file describing the analysis. Please constrain the text of the writeup to < 2000 words and the number of figures to be less than 5. It will make it easier for the graders to submit a repo with a gh-pages branch so the HTML page can be viewed online.

##Machine Learning Model

Tool: XGBoost, an implementation of tree-based extreme gradient boosting algorithm. A very fast and accurate method to do cross validation, fitting and predicting.

To view html report online, please click here.

project_report.Rmd: R markdown document for course project report.
project_report.html: Compiled html file for course project report.
data: Data folder containing csv files for training and testing sets.
prediction: Folder containing output of all 20 prediction files.
