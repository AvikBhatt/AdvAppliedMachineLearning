# Project 1
* In regression problems there is a continuous output(dependent) variable that we try to predict it's value within a range of input features.
* There is noise( $ϵ$ ) which means for esentially the same input there can be slightly different values for the output.
* The assumption is that noise follows a normal distribution with a mean of 0 and an unknown standard distribution.
* A simple representation is $y=f(X)+σϵ$
## Linear Regression
* For linear regression, the prediction is a weighted combination of input features.
  * Predicted Value = $weight_1 *$ Feature1 + $weight_2 *$ Feature2 +  etc... 
## Locally Weighted Regression
* Regardless if a given trend/association is linear or non-linear, at a local level they can be interpreted linearly.
  * Local properties are relative to the way we calculate the distance between two observations.
  * We use kernels for solving linear regression problems.
