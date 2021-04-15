# [Binary-Classification-Of-Sonar-Returns](https://github.com/kuluruvineeth/Binary-Classification-Of-Sonar-Returns/blob/main/Binary%20Classification%20of%20Sonar%20Returns.ipynb)

## Sonar Object Classification Dataset
* This is a dataset that describes sonar chirp returns bouncing off different surfaces.
* The 60 input variables are the strength of the returns at different angles.
* All of the variables are continuous and generally in the range of 0 to 1.
* The dataset contains 208 observations

## Building Baseline Neural Network Model 

## Improving Performance with the Data Preparation
* An effective data preparation schema for tabular data when building neural network models is **standardization**.
* This is where the data is rescaled such that mean value for each attribute is 0 and the standard deviation is 1.

## Tuning Layers and Neurons in the Model
* There are many things to tune on a neural network,such as the *weight initialization,activation functions,optimization procedure and so on*.
* One aspect that may have an outsized effect is the structure of the network itself called the **network topology**.
* Experiments on the structure of the network : making it smaller and making it larger.

  ### Evaluate a Smaller Network
  * we take our baseline model with 60 neurons in the hidden layer and reduce it by half to 30.
  * This will put pressure on the network during training to pick out the most important structure in the   input data to model.

 ### Evaluate a Larger Network
 * Here, we add one new layer to the network that introduces another hidden layer with 30 neurons after the first hidden layer.
 * 60 inputs -> [60->30] -> 1 output

## we can achieve model accuracy in the range of 80% to 85%.
  
