This repository contains implementation for logistic regression using python, only with numpy package. 
The dataset used to validate this algorithm is the titanic datset uploaded on Kaggle. 
Logistic regression modelsare used to predict numbers, these numbers correspond to the probability values of input data belonging to a particular class.The logistic function, also called the sigmoid function is used in applying weighted sum of input data. 
Age and Cabin columns had missing values. A Boxplot using the Matplotlip library was used to show relationship between age and Pclass. Handling null values in age with Pclass as correlation is high; using the mean ages for a particular class. Then the cabin column was dropped.

considering the Logistic regression, a function was defined with numpy, to pass the data through a sigmoid curve. Log-likelihood technique function was defined to estimate the most likely parameters for the model. To guarantee one local minimum during the optimization, a gradient descent fucntion was defined and implemented. 
The developed model was used to predict the titanic dataset and performance was checked.
