Name:srividya midasala

Company: CODTECH IT SOLUTIONS

Domain:Data Science

Intern Id:CTO8DS8884

Duration:OCTOBER to NOVEMBER 2024

Mentor:Santhosh kumar

Overview of the  Project:

This project focuses on predictive modeling using Linear Regression, a popular and fundamental machine learning technique used to model the relationship between a dependent (target) variable and one or more independent variables.

Objective
The objective of this project is to:

Build a simple linear regression model that predicts Salary based on Years of Experience.
Evaluate the model's performance using metrics like Mean Squared Error (MSE) and R² (R-squared score).
Visualize the relationship between the predicted and actual values to assess how well the model performs.

Project Workflow

Importing Libraries

numpy: For numerical operations.
pandas: For handling and analyzing the dataset.
matplotlib: For visualizing the regression line and predictions.
sklearn: To split the data, train the linear regression model, and calculate performance metrics.

Loading the Dataset:

The salary_data.csv dataset contains two columns:
YearsExperience (Independent variable)
Salary (Dependent variable)

Defining Variables

The independent variable (X) is Years of Experience.
The dependent variable (Y) is Salary.

Splitting the Data

The dataset is split into 80% training and 20% testing data using train_test_split.
Training data is used to train the model, and testing data is used to evaluate performance.

Training the Model

A Linear Regression model is trained using the LinearRegression class from sklearn.

Making Predictions

The trained model predicts salaries for the test data.
Evaluating the Model

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.

R² (R-squared Score): Indicates the proportion of the variance in the dependent variable that the independent variable explains.

Visualizing the Results

Training Data and Regression Line: Visualizes how well the regression line fits the training data.
Actual vs Predicted Values: Visualizes the difference between the predicted and actual values for the test set.

Sample Output:

Mean Squared Error (MSE):
java
Copy code
Mean Squared Error (MSE): 31270951.72
R-squared Score:
yaml
Copy code
R-squared Score: 0.95

Visualization:

A regression line showing the fit with the training data.

Scatter plots comparing the actual vs. predicted salaries.

Conclusion

If the MSE is low and the R² score is close to 1, the model performs well, indicating that Years of Experience is a good predictor of Salary.
This project demonstrates:

How to build a simple linear regression model.
How to use performance metrics to evaluate the model.
How to visualize data and predictions for better interpretation.

Applications

This project serves as an introduction to predictive modeling and can be extended to other datasets and machine learning models.
It highlights the importance of linear regression in finance, business forecasting, and HR analytics (e.g., salary predictions).


