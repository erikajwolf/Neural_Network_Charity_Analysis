# Neural_Network_Charity_Analysis

## Overview & Purpose

## Results
### Data Preprocessing
**-What variable(s) are considered the target(s) for your model?** An indication that the target has been funded by AlphabetSoup.
**-What variable(s) are considered to be the features for your model?** IS_SUCCESSFUL column was used in this model.
**-What variable(s) are neither targets nor features, and should be removed from the input data?** EIN and NAME can be removed to improve efficiency.

### Compiling, Training, and Evaluating the Model
**-How many neurons, layers, and activation functions did you select for your neural network model, and why?** Thhere were 120 neurons in layer one with relu activation, 80 neurons in layer 2 with relu activation, 40 neurons in layer 3 and 20 neurons in layer 4 (both with sigmoid activation). 
**-Were you able to achieve the target model performance?** No, the best the model could produce was 46.7%
**-What steps did you take to try and increase model performance?** STATUS and SPECIAL_CONSIDERATIONS columns were dropped. Neurons were increased and number of layers were increased.


## Summary

There was a 46.7% accuracy in the relu and sigmoid activations.

