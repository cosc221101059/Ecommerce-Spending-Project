
# **Ecommerce Spending Project**

# **Overview**

This project analyzes ecommerce spending patterns using a dataset that includes customer information and spending metrics. The objective is to build a linear regression model to predict the yearly amount spent by customers based on various features such as session length, time on the app, and length of membership.


# **Dataset**

The dataset used in this project contains the following columns:

- Email: Customer's email address.
- Address: Customer's address.
- Avatar: Customer's avatar color.
- Avg. Session Length: Average length of a customer's session on the website.
- Time on App: Time spent by the customer on the app.
- Time on Website: Time spent by the customer on the website.
- Length of Membership: Duration of the customer's membership.
- Yearly Amount Spent: Total amount spent by the customer in a year.

# **Analysis**

**Exploratory Data Analysis (EDA):**

The dataset is analyzed to understand the relationships between different features and the target variable (Yearly Amount Spent). 

**Various plots are used to visualize these relationships:**

- Jointplots: To explore the relationship between Length of Membership and Yearly Amount Spent.
- Pairplots: To examine the interactions between all features.
- Linear Regression Plots: To visualize the linear relationship between Length of Membership and Yearly Amount Spent.
- 
# **Model Building:**

A linear regression model is constructed using the following features:

- Avg. Session Length
- Time on App
- Time on Website
- Length of Membership
The model is trained on a training set and evaluated on a test set.

 # **Evaluation Metrics:**
The performance of the model is assessed using:

- Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.
- Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual values.

# **Dependencies**

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
