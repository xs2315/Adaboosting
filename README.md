# Adaboosting
1.  Implement the AdaBoost algorithm in R. The algorithm requires two auxiliary functions, to train and evaluatethe weak learner.  We also need a third function which implements the resulting boosting classifier.  We willuse decision stumps as weak learners, but a good implementation of the boosting algorithm should permityou to easily plug in arbitrary weak learners.  To make sure that is possible, please use function calls of thefollowing form:
2.  Implement the functionstrainandclassifyfor decision stumps.
3.  Run  your  algorithm on the USPS  data  (the  digit  data  we  used  in  Homework  2,  use  the  training  and  testdata for the 3s and 8s) and evaluate your results using cross validation.
4.  Plot the training error and the test error as a function of b.
