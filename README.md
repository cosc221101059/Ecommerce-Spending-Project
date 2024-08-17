Ecommerce Spending Project
Overview
This project analyzes ecommerce spending patterns using a dataset that includes customer information and spending metrics. The goal is to build a linear regression model to predict the yearly amount spent by customers based on various features such as session length, time on app, and length of membership.

Dataset
The dataset used in this project contains the following columns:

Email: Customer's email address.
Address: Customer's address.
Avatar: Customer's avatar color.
Avg. Session Length: Average length of a customer's session on the website.
Time on App: Time spent by the customer on the app.
Time on Website: Time spent by the customer on the website.
Length of Membership: Duration of the customer's membership.
Yearly Amount Spent: Total amount spent by the customer in a year.
Analysis
Exploratory Data Analysis (EDA):

The dataset is analyzed to understand the relationships between different features and the target variable (Yearly Amount Spent).
Various plots such as jointplots, pairplots, and linear regression plots are used to visualize these relationships.
Model Building:

A linear regression model is built using features like Avg. Session Length, Time on App, Time on Website, and Length of Membership.
The model is trained on a training set and evaluated on a test set.
Evaluation Metrics:

The performance of the model is assessed using Mean Squared Error (MSE) and Mean Absolute Error (MAE).

The main steps in the analysis are:

Loading the Data: Import the dataset and perform initial exploration.
Data Visualization: Create visualizations to understand the data better.
Model Training: Train a linear regression model using the training data.
Model Evaluation: Evaluate the model's performance using the test data and various metrics.
