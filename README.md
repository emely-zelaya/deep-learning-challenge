# deep-learning-challenge


## Overview of the Analysis

The purpose of this analysis was to create a deep learning model that can predict whether applicants for funding from Alphabet Soup will be successful. By analyzing historical data, the model aims to help the charity determine which organizations to fund.

## Results

### Data Preprocessing

- **Target Variable(s)**: The final model configuration included three hidden layers with 120, 75, and 35 neurons, respectively, using 'relu' and 'tanh' activation functions. This setup aimed to balance the model's ability to learn complex patterns without overfitting.

- **Feature Variable(s)**: The features included various categorical variables such as 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', and numerical variables like 'ASK_AMT', all after being preprocessed into a suitable format for the model.

- **Removed Variable(s)**:'EIN' and 'NAME' were removed from the input data as they are identifiers that do not contribute to the model's predictive capability.

![Preprocessing](https://github.com/emely-zelaya/PICTURES_GROUP3_PROJECT3/blob/main/image.png?raw=true)


### Compiling, Training, and Evaluating the Model

- **Neurons, Layers, Activation Functions**: The final model configuration included three hidden layers with 120, 75, and 35 neurons, respectively, using 'relu' and 'tanh' activation functions. This setup aimed to balance the model's ability to learn complex patterns without overfitting.

- **Achievement of Target Performance**: The model achieved an accuracy of approximately 72.5%, which is below the target performance of 75%.

- **Steps to Increase Performance**:  Attempts to improve the model included varying the number of neurons and layers, adjusting the activation functions, and implementing different training epochs to find the optimal configuration.

## Summary

The deep learning model performed moderately well but did not achieve the desired benchmark. It suggests a need for further optimization, possibly through more sophisticated preprocessing, hyperparameter tuning, or exploring different architectures.

As a recommendation, a different approach such as a Random Forest Classifier or Gradient Boosting Classifier could be employed. These ensemble methods are powerful for classification problems and may yield better performance due to their ability to model complex relationships and reduce variance through averaging multiple decision trees.

This report encapsulates the efforts and findings from using neural networks to address the classification problem for the Alphabet Soup charity.