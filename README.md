# Neural_Network_Charity_Analysis

### Overview 

The purpose of this analysis was to create a binary classifer which is capable of predicting if applicants will be successful if funded by a charity. In order to analyze the data, we decided to use three methods: pre processing data for neural network models, to complile, to train, and to evaluate the model, and finally optimizing

### Results:

- Data Preprocessing:
    - What variable(s) are considered the target(s) for your model?
IS_SUCCESSFUL Column

    - What variable(s) are considered to be the features for your model?
All columns but the IS_SUCCESSFUL Column

    - What variable(s) are neither targets nor features, and should be removed from the input data
EIN and NAME

-  Compiling, Training, and Evaluating the Model
    - How many neurons, layers, and activation functions did you select for your neural network model, and why? 
This was made out of 2 hidden layers. The first layer is 80 aneurons and the second layer is 30 neurons. that contained 80 and 30 neurons. ReLu is the activation function used for both hidden layers vs the output layer which is Sigmoid.

    - Were you able to achieve the target model performance?
Unfortunately I was not. According to the image below it shows I was only able to get to 72%.


### Summary:

With the model that we used, it seems like we did not reach the 75% accuracy target. Instead of using the binary classification situation, we could explore the Random Forest Classifier. In this model, we could combine multiple decision trees and generate a classified output that will evaluate its performance against the deep learning model.