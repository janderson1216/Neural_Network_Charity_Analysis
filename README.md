# Neural_Network_Charity_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
Supporting nonprofits and charitable organization with funding can carry significat risk. This analysis usesmachine learning and neural networks to predict whether applicants will be successful if funded by Alphabet Soup.

## Results: 

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
  - The tatrget of the model is IS_SUCCESSFUL
  
What variable(s) are considered to be the features for your model?
  - The features of the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
  
What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN and NAME were removed from the inpujt data
  
### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - The model uded two hidden layer (80 and 30 neurons). ReLu was used to activate the function, which is ideal for positive nonlinear input and Sigmoid was used for the output. 
  
Were you able to achieve the target model performance?
  - I was not succesful in reaching a model accuracy of 75%.
  
What steps did you take to try and increase model performance?
  - Increased the numb er of neurons for one of the hidden layers
  - Added a third hidden layer
  - Used "tanh" aactivation function

## Summary: 
The model accuracy did not reach performace target of 75%. A possible next step could be to use Random Forest classifiers, a sufficient number of estimators and tree depth should allow for a mjore robust and accurate model. 
