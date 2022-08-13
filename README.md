# Neural_Network_Charity_Analysis

# Overview
The purpose of this analysis was to use deep machine learning to help a company make better decisions in who they give their charitable donations to.  The data was first preprocessed for the model, then compiled and trained, and finally an attempt was made to optimize the model to reach 75% accuracy.

# Results
## Data Preprocessing

- The column of IS_SUCCESSFUL was used as it contains binary data and was determined to be the target for the model.
- The columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, AND ASK_AMT were used as the features for the model.
- The columns EIN and NAME were determined to have no bearing on the outcome and were removed.

## Compiling, Training, and Evaluating the Model

- The model was created with two hidden layers with 80 and 30 neurons using the ReLU activation.  The output layer was a single neuron and was activated with Sigmoid.
- The model came close to the goal of 75% but did not quite reach the target.
- To increase the effectiveness, I increased the number of neurons and also tried the tanh activation but was still unable to reach 75%.

# Summary

The target of 75% accuracy was not reached which leads me to believe that this model may not be effective enough to recommend.  Using a supervised machine learning model like RandomForestClassifier may be used to evaluate its performance against this model.
