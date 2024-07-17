# Learning-by-Building 1. 
Compilation of activities on building Regression and Classification models 

This is an overview of my activities and projects focused on building both regression and classification models specifically on Logistic and Linear Regression. The aim is to build as many projects as possible to understand the algorithms used in these models both theoretically and practically.


### Objective

The primary aim is to understand the mathematical logic behind key methods used in logistic regression, including the sigmoid function, cost function, gradients, and gradient descent. This approach emphasizes a direct mathematical understanding of how these methods determine the cost, coefficients, their derivatives, and the probability of outcomes.

### Methodology

1. **Sigmoid Function:**
   - Employed to compute the probability of the outcome. It maps any real-valued number into the range [0, 1].

2. **Cost Function:**
   - Used to measure the accuracy of the predictions made by the model. The logistic regression cost function ensures that the cost is minimized when predictions are accurate.

3. **Gradient Calculation:**
   - Derivatives of the cost function with respect to the coefficients (weights) and bias are computed. These gradients indicate the direction and magnitude of the adjustments needed to minimize the cost function.

4. **Gradient Descent:**
   - An optimization algorithm used to iteratively update the weights and bias to minimize the cost function. The learning rate controls the step size of these updates.

### Implementation

- **Initialization:** Weights and bias are initialized to zeros.
- **Cost and Gradient Computation:** Using the training data, the cost and gradients are calculated.
- **Optimization:** Gradients are used to update the weights and bias through gradient descent, aiming to minimize the cost function.
- **Prediction:** The optimized model predicts the probability of diabetes outcomes.

### Goal

The project provides a foundational understanding of logistic regression's mathematical methods and enhances comprehension of how these methods contribute to predicting probabilities of outcomes.


