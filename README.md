# Titanic_ML


## 1. Dealing with Missing Data


- Fill Missing Values in Age:  Replaces any missing values in the Age column with the mean age.
  

<img width="521" alt="image" src="https://github.com/user-attachments/assets/3155c5a4-df2e-4306-9a7d-562afbad6ea1">



- Filling missing Embarked values with the mode, you ensure that the Embarked column has no NaN values, which is necessary for consistent data processing and modeling.

  
<img width="519" alt="image" src="https://github.com/user-attachments/assets/4a701f81-5148-41f5-8c7f-cc8fb0a8d77a">


## 2. Drop useless columns


Drop PassengerId and Name Columns : 
<img width="620" alt="image" src="https://github.com/user-attachments/assets/56185c5e-2933-4bfd-a229-c1209fb6270f">


Why Drop These Columns?


PassengerId: This column is typically an identifier and does not contain useful information for modeling.


Name: While it contains passenger names, it's generally not useful for prediction tasks and is often removed to avoid clutter.


## 3. Dealing with Duplicates


Check if there are duplicates in the dataset:


<img width="378" alt="image" src="https://github.com/user-attachments/assets/198f5caa-6200-495c-a32e-1d1187de105d">


drop the duplicates:


<img width="467" alt="image" src="https://github.com/user-attachments/assets/4265cbad-ca98-47ff-a37a-9afa36f5d7b2">


## 4. Splitting the data into training data & Testing data


Splits the data into training (80%) and testing (20%) sets.


<img width="539" alt="image" src="https://github.com/user-attachments/assets/67a2eea8-f555-4b95-a8a1-5e2035430fc8">


## 5. Model Training


Create and Train Logistic Regression Model:


<img width="518" alt="image" src="https://github.com/user-attachments/assets/73e501d6-54d8-4fdc-a1f1-08c7b3b49445">


Scaling: Standardizes feature values to improve model performance and convergence.


Model Training: Trains a logistic regression model on the scaled data to predict the target variable.


## 6.Model Evaluation


Prediction: The model makes predictions on the test data.


Accuracy: Measures the proportion of correct predictions. An accuracy of 1.0 means the model predicted all test cases correctly.


<img width="350" alt="image" src="https://github.com/user-attachments/assets/baab688e-2c08-46b0-b40e-abc51bbe6946">
