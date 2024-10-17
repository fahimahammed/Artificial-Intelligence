# Artificial-Intelligence

## Assignments: 

### Assignment 1: Write a Python program to display values of y when 'x' is an independent variable having values [-10, 10, step_size = 0.1]
- y = wx + b; where 'w' and 'b' are constants
- y = x^2
- y = 1 / (1 + e^(-x))
- y = (e^x - e^(-x)) / (e^x - e^(-x))
- y = g(f(x)) where u = f(x) = wx + b and y = g(u) = 1/ (1 + e^(-u))
- y = g(f(x)) where u = f(x) = wx + b and g(u) = (e^u - e^(-u)) / (e^u + e^(-u))
- y = g3(f3(v)) where w = f3(v) = w3y1 + w4y2 + b & g3(w) = 1 / (1 + e^(-w)) | y1 = g1(f1(x)) where u1 = f1(x) = w1x + b1 & g1(u1) = 1 / (1 + e^(-u1)) | y2 = g2(f2(x)) where u2 = f2(x) = w2x + b2 & g2(u2) = 1/ (1 + e^(-u2))
- y = wsin(x) + b
- y = wx^2 + b
- y = we^x + b

### Assignment 2:
1. Build a CNN which exactly looks like VGG16. Transfer weights of pre-trained VGG16 to the newly built VGG16.

2. Build a CNN which will look like VGG16, but will not be exactly VGG16.

### Assignment 3:
Implement a simple deep neural network for solving the polynomial y = 5x^3 - 8x^2 - 7x + 1 with the following specifications:

- Use three hidden-layers of sizes 32, 64, and 128 and display the generated DNN with the required number of parameters.
- Generate training samples within the range of -20 to +20. Use the appropriate method for normalizing the training data in the range of -1 to +1.
- Use 5% of the samples as test data and 5% of the samples as validation data and the rest of the data for training the DNN with and appropriate number of epochs.
- Display the training accuracy vs validation accuracy and training error vs validation error curves.
- After training, use the test data for prediction and display the prediction accuracy vs true levels of the test data.

