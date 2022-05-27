# Neural Network Charity Analysis

## Analysis Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.\
We use the following methods for the analysis:
- preprocessing the data for the neural network model,
- compile, train and evaluate the model,
- optimize the model.

## Resources
- Data Source: [charity_data.csv](https://github.com/joZecodes/Neural_Network_Charity_Analysis/blob/main/charity_data.csv)
- Software: Python, Anaconda Navigator, Conda, Jupyter Notebook

## Results


### Data Preprocessing
1. What variable(s) are considered the target(s) for your model?   
Making sure that the target has been successfully funded by AlphabetSoup as indicated in the DataFrame, by checking the success mark.
2. What variable(s) are considered to be the features for your model?
A binary value indicating whether a charity donation was effectively used is in the column "is successful." This variable is then used to train our deep learning neural network.
3. What variable(s) are neither targets nor features, and should be removed from the input data?    
In order to increase code efficiency, the EIN and NAME columns can be removed.

### Compiling, Training, and Evaluating the Model
4. How many neurons, layers, and activation functions did you select for your neural network model, and why?  
Two hidden layers with 80 and 30 neurons each make up this deep-learning neural network model.
5. Were you able to achieve the target model performance? 
Under 75% of the charity donations were correctly predicted using the model. This is not a satisfying outcome.

6. What steps did you take to try and increase model performance?   
![Attempts.png](https://github.com/joZecodes/Neural_Network_Charity_Analysis/blob/main/Attempts.png) 
