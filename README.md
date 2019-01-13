# LinearRegression

Wine Quality prediction is performed in the attached jupyter notebook file using python's Linear regression model.

The wine quality dataset has been taken from UCI Machine Learning database repository.

Using the Ordinary Least Squares method , a linear regression model has been constructively created with every feature added to one another. Starting with univariate then moving to bivariate and all other higher features. This also known as greedy approach.

The AIC, BIC and Rsquare values resulted from each model are compared to the other model to arrive at a stopping condition.

Best features are selected as the ones which produced highest Rsquare values.

Stopping condition of a model is such that when the AIC value of one model reduces from the previous model.

Once the linear regression model has been created, the outliers in the given data is calculated by SSE values.

The top 5 outlier feature values are evaluated using the python inbuilt methods.
