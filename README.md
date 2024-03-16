# deep-learning-challenge
 
# Chad Fletcher
# Module 21
# Deep Learning Challenge


# Neural Network Model Report

# Overview of the analysis: 
The aim of this analysis was to develop a tool for the nonprofit foundation, Alphabet Soup, to aid in the selection of funding applicants with the highest likelihood of success.


# Results:

# Data Preprocessing
    - What variable(s) are the target(s) for your model?
        - IS_SUCCESSFUL
    - What variable(s) are the features for your model?
        - APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS
        - INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
    - What variable(s) should be removed from the input data because they are neither targets nor features?
        - EIN, NAME

# Compiling, Training, and Evaluating the Model
    - How many neurons, layers, and activation functions did you select for your neural network model, and why?
        - For my model I used 3 hidden layers. The first layer has 50 neurons and relu activation. The second layer has 15 neurons and relu activation. The final layer has 1 neuron and sigmoid activation. I chose this layout after various tests of adjusting neurons, layers, and activation functions to obtain the best results.
    - Were you able to achieve the target model performance?
        - I was not able to achieve the target performance, but I was able to come very close at 73%.
    - What steps did you take in your attempts to increase model performance?
        - After running my model for the first time I began making small adjustments in neurons, activation functions, and layers. I mainly focused on narrowing down the amount of neurons because I observed the most change when doing so.


# Summary: 
Overall, I am satisfied with the performance of my model. It came within 2% of the target accuracy, which is promising. However, to enhance the model's capabilities further, several avenues could be explored. Gathering additional data may provide more insights and improve accuracy. Experimenting with alternative algorithms could reveal better approaches for the dataset. Additionally, dedicating more attention to data cleaning processes might enhance the model further. These steps could lead to significant improvements in the tool's effectiveness for Alphabet Soup's funding applicant selection process.