# deep-learning-challenge

Overview of the Analysis:

The purpose of this analysis is to create a deep learning model to predict whether organizations funded by Alphabet Soup will be successful based on various features provided in the dataset. The goal is to achieve a predictive accuracy higher than 75%.

Results:

Data Preprocessing:

Target Variable:
The target variable for our model is "IS_SUCCESSFUL," which indicates whether an organization's funding application was successful (1) or not (0).
Features: The features used for the model include "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "STATUS," "INCOME_AMT," and "SPECIAL_CONSIDERATIONS."

Compiling, Training, and Evaluating the Model:

Neurons, Layers, and Activation Functions: We selected a neural network model with two hidden layers. The first hidden layer has 8 neurons with the ReLU activation function, and the second hidden layer has 5 neurons with the ReLU activation function. The output layer has 1 neuron with the sigmoid activation function to produce binary classification results. We chose this architecture to balance complexity and model performance.
Achieving the Target Model Performance: Our initial model achieved an accuracy of approximately 72.56%, which fell short of the target of over 75% accuracy.
s
Steps for Increasing Model Performance:

Summary:
In summary, our deep learning model's performance, as it stands, did not meet the target accuracy of 75%
