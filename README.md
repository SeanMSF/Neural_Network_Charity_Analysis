# Neural_Network_Charity_Analysis

The purpose of this analysis was to use deep learning neural networks to perform risk analysis with the aim of characterizing charitable organizations as effective stewards of donor money.

The dependent variable in question as the target of this model is the IS_SUCCESSFUL variable.

APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT are considered to be other features for the model.

What variable(s) are neither targets nor features, and should be removed from the input data?  NAME and EIN are removed.

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Were you able to achieve the target model performance?  No, we were not able to achieve accuracy above 75%. With more time, I would like to see what measures other students may have performed in order to increase performance of the model. 

What steps did you take to try and increase model performance? I attempted to add nodes, hidden layers and to reduce columns under consideration (dropped 2 affiliations).

Summary: the overall results of the deep learning model were to not perform with desired accuracy. A recommendation for how a different model could solve this classification might include to try a random forest. We can also continue to try adjusting the inputs of the model. We need to be clear on the aims of our models before tweaking variables.
