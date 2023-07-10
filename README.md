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
  * Try to add another layer and join 'EIN' and 'NAME' back but it does not work.
# Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
  * In my first model, I use to two layers, first is 80, and second is 30. And I reached the accuracy: 0.7243148684501648
  * In second model, I increase the layers and change the unit amount. The accuracy reached 0.7248979806900024
  * Third model was applied with new activation function. However, The accuracy is 0.7254810333251953. Tbere was no big change for that.
  * Finally, I export the third modle and save it as 'charity_data.h5'
