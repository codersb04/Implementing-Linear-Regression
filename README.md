# Implementing-Linear-Regression
## Task
Immplement a Linear Regression Model from Scratch.</br>
Tool Used: Jupyter Notebook, Python
## Description
### Linear Regression
**Y = wX + b**</br>
Y: Dependent Variable</br>
X: Independent Variable</br>
w: Slope or Weight</br>
b: Intercept or Bias</br>
### Gradient Descent
**w = w-L*Dw**</br>
**b = b-L*Db**</br>
w: Slope or Weight</br>
b: Intercepe or Bias</br>
L: Learning Rate(Rate ata which change occur)</br>
Dw: Change of Cost Function with respect to slope/ weight(w)</br>
Db: Change of Cost Function with respect to Intercept/ bias(b)</br>
## Building Linear Regression
- Intiating the parameters(Hyperparameters) that are learning rate and number of iterations
- Fit the data to the model
  1. Number of training examples and number of features
  2. Intiating weight(m: slope) and Bias(c: Intercept)
  3. Implementing the gradient Desent
- Update Model Parameter(values of Weight and Bias) and Calculate Gradient
- Predict the values
## Steps tp Build the best model
- Step 1: Set Learning rate and nuber of iteration and intiate a random weight value
- Step 2: Build Linear Regression Equation(Y = wX + b)
- Step 3: FInd "Y prediction" value for given x for corresponding weight(w) and bias(b)
- Step 4: CHeck the Loss function for each w and b(difference between y and y preiction)
- Step 5: Updare the parameter w and b according to Gradient descent. (new w and b)
- Step 6. repect step 3,4 and 5 till minimum loss function
## Implementing the model
- Import the necessary libraries
- Load the dataset and split the target and features column
- split into training and test data
- Load the build model and train it using the training data
- Predict by using test data
- Plot a graph to visualize the actual value and predicted values</br></br></br>


Reference: 7.1.5. Implementing Linear Regression from scratch in Python, Siddhardhan, https://www.youtube.com/watch?v=xfzMwzqcWJc&list=PLfFghEzKVmjsNtIRwErklMAN8nJmebB0I&index=86
