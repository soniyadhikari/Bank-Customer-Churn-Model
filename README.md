# Bank Customer Churn Model

## Overview
This project aims to predict customer churn in a bank using a Support Vector Machine (SVM) classifier. The model utilizes a dataset containing various customer attributes such as credit score, geography, gender, age, tenure, balance, and number of products. By analyzing these features, the goal is to identify patterns that indicate whether a customer is likely to leave the bank.

## Dataset
The dataset used for this project can be found [here](https://github.com/YBI-Foundation/Dataset/raw/main/Bank%20Churn%20Modelling.csv). It includes information necessary for training and evaluating the churn prediction model.

## Project Structure
The project is structured as follows:

### Data Preparation and Exploration
- Importing and loading the dataset.
- Exploring the structure and summary statistics of the data.
- Encoding categorical variables and transforming features as needed.

### Data Preprocessing
- Handling missing values and outliers.
- Scaling numerical features for uniformity.
- Balancing the dataset to address class imbalance using appropriate techniques.

### Model Development
- Splitting the data into training and testing sets.
- Building and training a Support Vector Machine (SVM) classifier.
- Evaluating the model's performance using metrics such as accuracy, precision, recall, and F1-score.

### Hyperparameter Tuning
- Optimizing model performance through hyperparameter tuning using techniques like GridSearchCV.
- Selecting the best set of parameters to maximize model accuracy and reliability.

### Results and Discussion
- Analyzing and interpreting the model's predictive capabilities.
- Discussing insights gained from the analysis and implications for reducing customer churn.

## Dependencies
To run the project, ensure you have the following dependencies installed:
- Python 3.x
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

## Conclusion
This project demonstrates the application of machine learning techniques to predict and mitigate customer churn in banking, offering a structured approach to analyzing customer data and implementing predictive models for business insights.
