# K_Nearest_Neighbors

This repsitory aims at understanding the KNearest Neighbors estimator. It is a technique which can be used for
prediction and classification as well. It operates on the equation of 'Minskowski distance'. It is made for distance
between data points in p dimension. When p=2, it is known as Euclidean distance. 

Regression:

Predictions are made by averaging the 'k' nearest neighboring datapoints.

Classification:

Classification is done on basis of mode of 'k' datapoints.

The algorithm is worked on the famous iris dataset. The number of neighbors used can be varied, and hence the decision boundary
shifts itself according, aka, learns/adapts itself.

![knn1](https://user-images.githubusercontent.com/55191934/77160163-d2c1a480-6acc-11ea-9e61-3d6b6863a7ea.PNG)

When the number of neighbors increase, the decision boundary smoothens or flattens out:

![knn2](https://user-images.githubusercontent.com/55191934/77160216-ec62ec00-6acc-11ea-8d3a-9de297640515.PNG)

With every estimator comes the bias vs. variance tradeoff. Hence an optimal solution must be sought to this. Concerning the iris dataset, here is a graph which shows the optimal number of neighbors vs the accuracy score.

![knn3](https://user-images.githubusercontent.com/55191934/77345980-70ca9e80-6d5b-11ea-85f5-3eab35cd75f1.PNG)

