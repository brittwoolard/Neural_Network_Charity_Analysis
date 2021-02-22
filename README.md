## Overview of the analysis: 

The goal of the project is to help foundation predict where to make investment. It uses features in provided dataset to develop a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The dataset contains over 34,000 organizations that have been funded by alphabet soup


## Results: 

### Data Preprocessing

#### What variable(s) are considered the target(s) for this model? 
- The variable we are targeting in this module is the IS_SUCCESSFUL column.

#### What variable(s) are considered to be the features for this model? 

* APPLICATION_TYPE
* AFFILIATION
* CLASSIFICATION
* USE_CASE
* ORGANIZATION
* STATUS
* INCOME_AMT
* SPECIAL_CONSIDERATIONS
* ASK_AMT

#### What variable(s) are neither targets nor features, and should be removed from the input data?

* EIN
* NAME

### Compiling, Training, and Evaluating the Model
#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
Used input features and 2 hidden layers
* number_input_features = 43
* hidden_nodes_layer1 = 80
* hidden_nodes_layer2 = 30

#### Were you able to achieve the target model performance?
No; I was able to acheive 64.8% accuracy

#### What steps did you take to try and increase model performance?

-  Increasing the number of hidden layers to include a 3rd
- Changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer

 
## Summary
The target accuracy was not achieved despite trying other methods to improve the performance. Perhaps having more dataset and features will help 
