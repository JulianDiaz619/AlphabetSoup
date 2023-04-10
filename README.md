# Alphabet Soup

## Purpose of analysis:
The purpose of this analysis was to create a deep learning neural network model using TensorFlow that would be able to classify whether or not a charity donation would be successful based on the organization's features such as the organization's type, area of focus, and income.

## Results:
### Data Preprocessing
* The target variable for the model is the "IS_SUCCESSFUL" column, which indicates whether or not a charity donation was successful.
* The features for the model include all the other columns in the dataset except for the "EIN" and "NAME" columns which are neither targets nor features, and should be removed from the input data.
### Compiling, Training, and Evaluating the Model
* For the neural network model, I selected two hidden layers, the first one having 80 neurons and the second one having 30 neurons. The activation function used in the hidden layers was ReLU, and the output layer had one neuron with a sigmoid activation function to produce a binary output.
* I was not able to achieve the target model performance of an accuracy higher than 75%. The highest accuracy achieved was 73% after several attempts to optimize the model.
* To try and increase the model's performance, I removed insignificant columns from the dataframe, added more hidden layers, and changed the number of neurons. However, these changes did not result in a significant improvement in the accuracy of the model.
Summary:
In conclusion, the deep learning model created using TensorFlow was not able to achieve the target model performance of an accuracy higher than 75%. Despite the attempts to optimize the model, the highest accuracy achieved was only 73%. It is possible that a different model such as a Random Forest or Gradient Boosting algorithm might be more effective in solving this classification problem. These models are capable of handling high dimensional datasets and can often be easier to tune and faster to train. Another possible solution is to explore other preprocessing techniques such as feature selection or feature engineering to see if they can help improve the model's performance.
