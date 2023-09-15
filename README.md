# deep-learning-challenge

Overview of the Analysis:

The purpose of this analysis is to create a deep learning model to predict whether organizations funded by Alphabet Soup will be successful based on various features provided in the dataset. The goal is to achieve a predictive accuracy higher than 75%.

Results:

Data Preprocessing:

Target Variable:
The target variable for our model is "IS_SUCCESSFUL," which indicates whether an organization's funding application was successful (1) or not (0).
Features: The features used for the model include "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "STATUS," "INCOME_AMT," and "SPECIAL_CONSIDERATIONS."

Compiling, Training, and Evaluating the Model:

Neurons, Layers, and Activation Functions: We selected a neural network model with two hidden layers. The first hidden layer has 80 neurons with the ReLU activation function, and the second hidden layer has 30 neurons with the ReLU activation function. The output layer has 1 neuron with the sigmoid activation function to produce binary classification results. We chose this architecture to balance complexity and model performance.

Achieving the Target Model Performance: The initial model achieved an accuracy of approximately 72.56%, which did not meet the predefined target accuracy of over 75%. To improve model performance, we followed these steps:

Steps for Increasing Model Performance:

1. Hyperparameter Tuning: We employed the Keras Tuner library to optimize hyperparameters, including the choice of activation function, the number of hidden layers, and the number of neurons in each hidden layer
2. Hyperband Search: We used the Hyperband search strategy for hyperparameter tuning, aiming to find the best model configuration within a limited number of iterations.

Results summary:

After hyperparameter tuning, the best model achieved an accuracy of 72.70%. While this is an improvement over the initial model, it still falls short of the target accuracy of 75%.

Further optimization or consideration of different model architectures and techniques may be required to meet the desired performance threshold.
