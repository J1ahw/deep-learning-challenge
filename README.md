# deep-learning-challenge

# Overview of the analysis: Explain the purpose of this analysis.

# Results: Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing

* What variable(s) are the target(s) for your model?
  * IS_SUCCESSFUL is target column
* What variable(s) are the features for your model?
  * all other columns are features excludeing 
* What variable(s) should be removed from the input data because they are neither targets nor features?
  * 'EIN' and 'NAME'
* Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
  * first layer is 9 neurons and second layer is 18 neurons.
* Were you able to achieve the target model performance?
  * not really, accuarcy is only 72%
* What steps did you take in your attempts to increase model performance?
  * Try to add another layer 
# Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
  * Although the accuarcy is only 72%, it did not reach 75%. But I still think it is a good model. May be we can find some more feature which might increase accuarcy. Even we got lots of feature columns becasue of dummy variables, it does not make model more comprehensive.
