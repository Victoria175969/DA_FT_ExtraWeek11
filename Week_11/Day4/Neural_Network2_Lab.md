
# Neural Network Lab

Welcome to the second Neural Network Lab! This time you will tackle a classification problem using the titanic spaceship data from week 7, where your goal is to predict if a passenger is going to be transported to a different dimension given their features (gender, cabin, etc).

### Steps to follow:

1. **Load the Data**  
   Load the titanic spaceship dataset. Ensure the dataset is clean and ready for analysis.

2. **Preprocessing**  
   Complete the following preprocessing steps:
   - **Split the data** 
   - **Encode categorical variables** 
   - **Scale numerical variables** 

3. **Create the Neural Network Class**  
   Implement a neural network model. The model should:
   - Take the passenger features as input.
   - Output if the passenger is sent to another dimension or not (binary problem). Remember to implement the Sigmoid function in the output layer!

4. **Train the Network**  
   Train the neural network on the training dataset. Use appropriate loss functions (e.g., BCELoss ) and optimizers (e.g., Adam, SGD). Tune hyperparameters like learning rate and epochs.

5. **Evaluate the Model**  
   Evaluate the neural network performance on the testing dataset. Use evaluation metrics like **Accuracy** to assess model accuracy.

6. **Logistic Regression Model**  
   - Train a simple **Logistic Regression** model on the same dataset.
   - Evaluate the logistic regression model using the same metrics as the neural network.

7. **Compare the Performances**  
   - Compare the performance of the neural network and logistic regression models.
   - Which model would you choose for this task? Justify your answer based on the performance metrics and potential trade-offs.
