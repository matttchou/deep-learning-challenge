# deep-learning-challenge
deep-learning-challenge

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup. -->
The report should contain the following:
Overview of the analysis: Explain the purpose of this analysis.
Results: Using bulleted lists and images to support your answers, address the following questions:
Data Preprocessing
What variable(s) are the target(s) for your model?

Answer The target is the Is-Successful column.

What variable(s) are the features for your model?

Answer The features list of this model are the follwoing: name application type, affiliation classifcation use case_organization income special consideration and ask amount.

What variable(s) should be removed from the input data because they are neither targets nor features?

Answer EIN (Employee Identification Number)

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

Answer For this model, 3 hidden layers each with many neurons because the compute seems to increase accuracy abouve 75%. This is expensive and timely. The first activation is relu and the other layers are sigmoid. It might boost accuracy using these functions. Readjusting my data that names as a get dummies can factor in with better scores.

Were you able to achieve the target model performance?

Answer Yes

What steps did you take in your attempts to increase model performance?

Answer Required to convert names into data points which had the biggest impact on improving the efficiency but was costly. It requires adding a third layer using sigmoid activation functions.

Summary: Summarize the overall results of the deep learning model.
Answer Overall, the accuracy is above 75%. We are able to classify each point in the test data in the 75% of the time. An applicant has an 80% chance of being successful if they follow this:

Name of applicants appears more than 5 times Type of applications following T3, T4, T5, T6, T7, T8, T9, T10, T19 Application of following classifcation...

Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
RandomForest mdel
