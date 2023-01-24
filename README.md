# Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement -- a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks.

One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website [here](http://groupware.les.inf.puc-rio.br/har)

# Data

-   The training are available [here](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv).

-   The test data are available [here](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv).

-   More information is available from the website [here](http://groupware.les.inf.puc-rio.br/har).

# Goal

The goal of your project is to predict the manner in which they did the exercise. This is the *"classe"* variable in the training set. You may use any of the other variables to predict with.
# the Executive summary

Using a random forest classifier with a k-fold cross validation of 7, the optimal model has an accuracy of 0.992 and an OOB rate of 0.66%. The variable importance plot shows that the roll_belt variable was most important in predicting the classe variable.

Applying our model on the test set, we attain a similar accuracy of 0.993. Applying the model on the 20 test case in our validation set, we achieve 100% accuracy in predicting the right classe variable. report will describe how we built the model, how we used cross validation, what is the expected out of sample error is, and what is the choices i did.




