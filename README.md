# Debug-in-KNN
Regarding the KNN model in Python, let's say 10-KNN, if the number of 10th nearest neighbors has two or more, python will randomly choose a y and then calculate the yhat.
In that case, every time we use KNN regression in python will lead to different results.
The idea to debug it is to invovle all the y if their x's distance to target x are same. In this way, the regression maybe become 11-KNN or even 100-KNN. But we will get a identical result.
