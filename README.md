![readme_image](https://github.com/KarimiNyaga/Phase_3_Project/assets/133044097/43377bb2-c612-4369-b442-f64af454c7d8)

# Predictive Modelling To Predict Customer Churn Rate

# Overview
1. Overview of Project
2. Business Problem
3. Data Understanding and Exploration
4. Data Preparation
5. Feature Engineering
6. Preprocessing
7. Modelling
- Logistic Regression
- KNearest Neighbors
- Decision Tree
- Random Forest
8. Conclusion and Next Steps

# Overview
This project analyses different aspects about a customer's account at a fictional telecommunications company, SyriaTel. The aspects I have used are:how long a customer has had an account, how long they spend on calls, how much they are charged for the call, whether or not they have a voice mail plan, and whether or not they have an international plan. The goal is to use machine learning models to help SyriaTel predict whether or not they will lose a customer. 

# Data 
The dataset is public and obtained from CrowdAnalytix as part of a prediction competition. The file is contained in the repository under the "Data" Folder. In the same folder is a file with a full description of the columns in the dataset. 

# Methods and Results
I started with Logistic Regression to create a baseline model. The second model created was built on KNearest Neighbors, chosen because of the size of the dataset. KNN works well with data that is not too large. 
The third model used is Decision Tree. The fourth model used is Random Forest, used as a step-up from Decision Tree. Random Forest works similarly to Decision Tree, but introduces more variance and consequently reduces the risk of overfitting. I have used GridSearch to tune all the models. This is because of the efficiency it offers in being able to tune multiple hyperparameters at once. The results from modelling can be summarised as follows:
![Screenshot 2023-10-23 220934](https://github.com/KarimiNyaga/Phase_3_Project/assets/133044097/e8271eb7-9d73-48f4-896d-44410c8008b5)


# Conclusion and Next Steps
- SyriaTel can successfully use the Random Forest model to predict their churn rate and therefore put appropriate measures to retain their customers.

 - SyriaTel should closely monitor changes in their data. Changes in the dataset will change the distribution of the data and therefore affect the predictions that the model is able to make.

 - Most models had the risk of overfitting. This is because of the collinearity of the features of the dataset. SyriaTel should aim to collect more information about their customers that can possibly help predict churn better, eg Customers' age, gender, profession.

# Instructions
To run the code, make sure you have the following:

- Python
- Jupyter Notebook
- You install both by using Anaconda. Find additional installation resources here
[External Installation Guide](https://www.geeksforgeeks.org/how-to-install-jupyter-notebook-in-windows/)
Navigate to the directory where you have cloned this repository and run Jupyter Notebook

Note that the method used for tuning is GridSearch, which is computationally expensive and execution time may take more than two minutes, depending on the kind of machine you are using. 

- This is what the notebook should look like:
  


https://github.com/KarimiNyaga/Phase_3_Project/assets/133044097/661dd758-c30c-4918-a4c7-ee63d4479aa8

# Repository Structure
├──  data
├──  code preview
├──  README.md
├──  Jupyter Notebook
├──  Non technical Presentation


