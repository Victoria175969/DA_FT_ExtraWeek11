
# Neural Network Lab

Welcome to the Neural Network Lab! You will apply your newly acquired knowledge on neural networks to tackle a regression problem. You will work with the auto insurance company data from week 2, where your goal is to predict the **total claim amount** of a customer based on their features (income, gender, region, etc).

### Steps to follow:

1. **Load the Data**  
   Load the auto insurance dataset. Ensure the dataset is clean and ready for analysis.

2. **Preprocessing**  
   Complete the following preprocessing steps:
   - **Split the data** into training and testing sets.
   - **Encode categorical variables** such as gender and region (use one-hot encoding or label encoding).
   - **Scale numerical variables** like income and claim amounts to ensure smooth model training (using techniques like standardization or normalization).

3. **Create the Neural Network Class**  
   Implement a neural network model using `PyTorch`. The model should:
   - Take the customer features as input.
   - Output the predicted total claim amount.

4. **Train the Network**  
   Train the neural network on the training dataset. Use appropriate loss functions (e.g., Mean Squared Error) and optimizers (e.g., Adam, SGD). Tune hyperparameters like learning rate and epochs.

5. **Evaluate the Model**  
   Evaluate the neural network performance on the testing dataset. Use evaluation metrics like **Mean Squared Error (MSE)** or **R-squared** to assess model accuracy.

6. **Linear Regression Model**  
   - Train a simple **Linear Regression** model on the same dataset.
   - Evaluate the linear regression model using the same metrics as the neural network.

7. **Compare the Performances**  
   - Compare the performance of the neural network and linear regression models.
   - Which model would you choose for this task? Justify your answer based on the performance metrics and potential trade-offs.
