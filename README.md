# deep-learning-challenge

### Overview of the analysis

The purpose of this analysis is to help Alphabet Soup predict applicatants success if funded by Alphabet Soup. 

### Results:

#### Data Preprocessing

•	Question : What variable(s) are the target(s) for your model?
  Answer: IS_SUCCESSFUL is the target variable for the model   Was the money used effectively

•	Question : What variable(s) are the features for your model?
  Answer: The other varibles ASK_AMOUNT, SPECIAL_CONSIDERATIONS , INCOME_AMOUNT, STATUS, ORGANIZATION, USE_CASE, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION are the 
  feature variables

•	Question : What variable(s) should be removed from the input data because they are neither targets nor features?
  Answer: EIN columns need to be removed fromt the input data as they are neither the targets nor the features

#### Compiling, Training, and Evaluating the Model

•	Question - How many neurons, layers, and activation functions did you select for your neural network model, and why?
  Answer- To train my model , Initially I selected neural network model to use 2 hidden layers , 80 and 30 neurons and activation function as Relu for the hidden layers and     
  Sigmoid for Ouput layer
  
•	Question - Were you able to achieve the target model performance?
  Answer- By Optimizing the model to use 3 hidden layers with 100, 20 and 10 neurons in first,second and third hidden layer respectively I was able to acheive 79% accuracy.
  
•	Question - What steps did you take in your attempts to increase model performance?
  Answer : I increased the model performance by increasing the number of hidden layers and also changing the neurons in hidden layers to ( 100,20 and 10 neurons- for first,second 
  and third hidden layer respectively) and chose activation function as relu for first and sigmoid for other 2 hidden layers

### References
Data collected from IRS. Tax Exempt Organization Search Bulk Data Downloads. 
https://www.irs.gov/
