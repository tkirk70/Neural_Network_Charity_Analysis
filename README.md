# :gift_heart: Neural_Network_Charity_Analysis :gift:
## OSU Module 19 - Neural Networks


### Overview of the analysis: Explain the purpose of this analysis.

  - Using machine learning and neural networks, find features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

### Results: Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing
  * What variable(s) are considered the target(s) for your model?
    - Using the IS_SUCCESSFUL column for our target - binary 'yes' or 'no'.
  * What variable(s) are considered to be the features for your model?
    - Columns 'APPLICATION_TYPE', AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS' were kept as features.
  * What variable(s) are neither targets nor features, and should be removed from the input data?
    - Columns "EIN" and "NAME" were dropped as they did not add to the model.

Compiling, Training, and Evaluating the Model
  * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - Starting out with 80 neurons in the first layer and 30 in the second.
    - During optimization, upped it to 100 and 50.
  * Were you able to achieve the target model performance?
    - Initially achieved ~ 72%
    - Subsequent attempts did not achieve much of an increase.
  * What steps did you take to try and increase model performance?
    - Aside from increasing the neurons, experimented with changing the 'activation', removing columns one by one.

### Summary:

  * Removing columns one at a time to see if the model improved is a tedious process and could be improved.
  * Similarly, using different activations without knowing the math behind them is just trial and error.
  * No one column of data seemed to make a great difference in the outcomes.
  
  * Recommendations
    - Figure out a way to see which columns have the greatest influence on the model.
    - Check other similar studies about credit risk and see what neural networks were used to make predictions.
