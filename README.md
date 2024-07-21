# Predicting_scrore_using_linear_regression
Project Overview
This project involves building a machine learning model to predict the percentage of a student based on the number of hours they study. The task is to use a simple linear regression algorithm to create a predictive model. This is a part of The Spark Foundation's Data Science & Business Analytics Internship tasks.

## Table of Contents
Project Overview
Dataset
Requirements
Installation
Usage
Model
Results

## Dataset
The dataset used for this project consists of two columns:

Hours: Number of hours a student studies.
Scores: The percentage scores of the student.

## Sample Data
Hours	Scores
2.5	21
5.1	47
3.2	27
8.5	75
3.5	30

## Requirements
Python 3.7 or above
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

 ## Installation
1. Clone the repository:
   git clone https://github.com/yourusername/predicting-student-scores.git
   cd predicting-student-scores

2. Install the required packages:
   pip install -r requirements.txt

## Usage
1. Open the Jupyter Notebook:
   jupyter notebook
Open the Predicting_Student_Scores.ipynb notebook.

Run the cells in the notebook to see the step-by-step implementation of the linear regression model.

Model
Linear Regression
The linear regression model is used to predict the scores of a student based on the number of hours they study. The relationship between the variables is assumed to be linear.

## Steps Involved
1.Data Importing: Load the dataset.
2.Data Exploration: Visualize the data using scatter plots.
3.Data Preparation: Split the data into training and testing sets.
4.Model Training: Train the linear regression model on the training data.
5.Model Prediction: Predict the scores on the testing data.
6.Model Evaluation: Evaluate the model performance using metrics like Mean Absolute Error (MAE).

## Results
The model was able to predict the scores with reasonable accuracy.
The predicted scores were close to the actual scores, indicating a good fit for the linear regression model.
Sample Output
For a student who studies 9.25 hours per day, the predicted score is approximately 92%.
