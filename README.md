# Machine_learning-Project2
📝 Project Documentation Overview
----------------------------------
This machine learning project focuses on predicting the Performance Index of students based on study-related inputs. The pipeline follows a structured approach from data loading to model evaluation.

📥 Importing Required Libraries
---------------------------------
Includes essential libraries such as:
pandas and numpy for data manipulation
scikit-learn for preprocessing, model training, and evaluation

📊 Data Loading and Inspection
--------------------------------
Data is loaded using pandas.read_csv().
Initial exploration is done using .head(), .info(), and .describe() to understand the structure, data types, and statistical summary.

🧹 Data Preprocessing
------------------------
Handling Missing Values: Checking and managing missing values if any.
Categorical Encoding: Converting categorical columns like 'Completed_Assignment' into numeric format using LabelEncoder.
Feature-Target Split: Separating the dataset into independent features and the target variable (Performance Index).
Train-Test Split: Using train_test_split from sklearn to create training and testing datasets.
Feature Scaling: Applying StandardScaler to normalize input features.

🧠 Model Building
-------------------
A Linear Regression model is used from sklearn.linear_model.
The model is trained on the scaled training data.

📈 Model Evaluation
---------------------
Model performance is evaluated using:
R² Score: To measure the goodness of fit.
Mean Absolute Error (MAE): To assess prediction error.
Mean Squared Error (MSE): To capture the average squared difference between actual and predicted values.
