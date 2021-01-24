# Funding Analysis using Neural Networks
The objective of this project is to analyse past funding resultTo use knowledge attained from Machine learning and neural networks creating a binary classifier that is capable of predicting if an applicant will be successful, if funded by the company (Alphabet Soup).

### Purpose
The company would like to know if the charity organization if funded is actually successful with the charity work. Desiring to implement machine learning and neural network to optimize the model in order to achieve accuracy in successful organization funding.

### Resources
Data Source CSV file: Charity_data.csv
VS Code v 1.52.1
Python 3.7.9
Pandas
Scikit-Learn
TensorFlow v2.4.0

### Results
A. Preprocessing Data for Neural Network model
This model target variable considered is - IS_SUCCESSFUL
The rest of the data is considered as the features. All data was used in order to have sufficient input data available
columns that I felt had no relation to the data are EIN, NAME and ORGANIZATION.
But when optimizing the model, i did decide to keep the Organization feature to see if there were any major changes.
B. Clean, Compile, train and Evaluate the model
Initial model the number of layers, neurons, activation functions and epochs are shown below.
Since this is a binary Classifier model a basic neural network model is said to have 2 to 3 times the input
the length of the trained data for the number of inputs
Although many trials were done to try and achieve the target model performance, none of the model optimizers done had an effect.
Modifying hidden layers increasing the number
although 3 layers were the max i went with thinking the data is being over fit.
Epochs started small and increased them to see any changes. none made any improvement.
Additional feature was removed to see possible outcome.