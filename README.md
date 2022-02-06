![](images/Undersampling.png) - for screenshots, remove before submitting


# Neural_Network_Charity_Analysis

## Overview of the Analysis
#Explain the purpose of the analysis

## Results

### Data Preprocessing

* What variable(s) are considered the target(s) for your model?
        The target for the model is the "IS_SUCCESSFUL" variable.
        ![](images/target.png)
* What variable(s) are considered to be the features for your model?
        The following are considered to be the features variables:
        ![](images/features.png)

* What variable(s) are neither targets nor features, and should be removed from the input data?
        The "EIN" and the "Name" variables need to be removed from the input data.
        ![](images/no_target_feature.png)

### Compling, Traning, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Neurons: neurons were set to the number of input features.  In this case there were 9.

* Were you able to achieve the target model performance?  No

* What steps did you take to try and increase model performance?
1. Removed the "AMT" variable:
        ![](images/optimization_v1.png)

2. Increased nodes in the hidden layers:
        ![](images/optimization_v2.png)

3. Decreased nodes in the hidden layers:
        ![](images/optimization_v3.png)


## Summary
#Summarize the overall results of the deep learning model. 
#Include recommendations for how a different model could solve this classifification problem, and explain your recommendation.