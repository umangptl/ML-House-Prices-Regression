# Machine-Learning-House-Prices
This project utilizes regression manual calculations of the cost function and gradient descent algorithm for predicting house prices based on a provided CSV data file. The model is tested with specific data inputs and trained to generate a sample submission file for the output.

## Dataset
The predictions are made using a dataset containing relevant features and corresponding house prices. The CSV data file serves as the input for the regression model. Due to file size limitations, the specific details and structure of the dataset are not included in this README.

## Cost Function
The CostFunction function calculates the cost associated with the predicted house prices compared to the actual prices. It computes the mean squared error (MSE) between the predicted values (x.dot(m) + theta) and the actual values (y). The cost is then divided by 2 times the number of samples for normalization purposes.

## Gradient Descent
The GradientDescent function performs the gradient descent optimization algorithm. It iteratively updates the values of m (slope) and theta (intercept) to minimize the cost function. The algorithm calculates the predictions (x.dot(m) + theta), computes the loss between the predictions and the actual values, and then calculates the gradients of m and theta based on the loss. These gradients are used to update the values of m and theta by multiplying them with the learning rate (learning_rate). The process is repeated for the specified number of epochs.

## Testing and Submission
The model is tested with specific data inputs to evaluate its performance and accuracy in predicting house prices. Once the testing phase is complete, the model is trained on the entire dataset to generate a sample submission file. This file contains the predicted house prices based on the learned patterns from the training data.

