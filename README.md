# Regression-using-Neural-Networks

Neural Network models (supervised) for Regression to create a model that predict the price of Diamonds

## Data-Set
This classical dataset contains the prices and other attributes of almost 54,000 diamonds. The dataset has been attached with the name "Diamonds.csv".

### Dataset’s Features Description:

* price in US dollars ($326 - $18,823) (Target)

* carat weight of the diamond (0.2 - 5.01)

* cut quality of the cut (Fair, Good, Very Good, Premium, Ideal)

* color diamond color, from J (worst) to D (best)

* clarity a measurement of how clear the diamond is  (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))

* x length in mm (0 - 10.74)

* y width in mm (0 - 58.9)

* z depth in mm (0 - 31.8)

* depth total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)

* table width of top of diamond relative to widest point (43 - 95)

## The Jupyter Notebook (Code)
First, I did a preprocessing for the data set. 

Then, I build 3 different models using different topologies by using the MLPRegressor, with a constant learning rate of 0.001.

After that, I used the mean squared error (MSE) as a loss function to calculate the evaluate the prediction model.

Finally, I recorded all the results/performance of all the used models.
