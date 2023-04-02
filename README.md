# The-Sparks-Foundation-Internship
Simple Linear Regression Model for Hours and Scores Data
This project applies supervised learning to a simple dataset containing the number of hours studied and the corresponding score achieved. The aim of the project is to create a simple linear regression model to predict the score based on the number of hours studied.

Dataset
The dataset used in this project contains 25 observations, each with two variables: hours studied and score achieved. The dataset is stored in a CSV file named hours_scores.csv.

Dependencies
This project requires the following Python libraries:

numpy
pandas
matplotlib
scikit-learn
To install these dependencies, you can use pip:

Copy code
pip install numpy pandas matplotlib scikit-learn
Model Building
The model is built using scikit-learn's linear regression class. The data is split into training and testing sets using scikit-learn's train_test_split function. The model is then trained on the training set and evaluated on the testing set.

The model's performance is evaluated using the root mean squared error (RMSE) and the coefficient of determination (R-squared) metrics.

Results and Insights
After building the model and evaluating its performance, some insights can be gained from the data. For example, we can see that there is a strong positive correlation between the number of hours studied and the score achieved. Additionally, the linear regression model provides a good fit to the data, with a low RMSE and a high R-squared value.

Finally, some insights on random numbers are also displayed.

Conclusion
In conclusion, this project demonstrates how to build a simple linear regression model to predict the score achieved based on the number of hours studied. The results show a strong positive correlation between the two variables and a good fit of the linear regression model to the data. The insights on random numbers provide some additional information about the data.
