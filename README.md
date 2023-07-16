# Used car price prediction


Sometimes selling your used car becomes crucial as we are not able to identify its fair price accurately. The depreciation of a car depends on a variety of factors so the car owner needs to be aware of the worth of their vehicle.

With the rapid expansion of Machine Learning, this problem can also be solved by minimizing human efforts and time. Let’s see an end-to-end solution for a similar problem.

Dataset Overview : 

The dataset used for the purpose of this report was downloaded from 
https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data
The data set consist of 4.5L Rows & 26 columns. 
Some of the features used to predict the price are year , Region , Manufacturer , Model , Cylinder , Fuels , odometer , Transmission , Size Type , Paint Color  & Description. 

We shall be evaluating 3 machine learning techniques in this project - 
Linear Regression
GBT regressor
Random Forest
The evaluation of the machine learning models shall be done on the basis of -
Mean Absolute Error (MAE)
Root Mean Absolute Error (RMSE)
R2 score

## Conclusion

GBT has the least MAE score of 0.6534 out of all the models
The sample prediction of GBT model is also the closest to the actual value
Therefore,GBT regression has the best accuracy followed by random forest and linear regression

## Future Scope

Applying more regression models like xGboost regression,  Ada boost and custom stacking regressor to get better accuracy
Using ensemble modelling 
Increasing the depth of GBT
We plan to utilize Deep Neural Networks to improve our prediction performance while avoiding overfitting. In addition to this, we shall tune Decision-Tree parameters like the number of trees, depth, etc. and sub-sample datapoints.
