# Heart Attack Prediction

This project aims to perform a classification on the provided dataset of Heart Attack prediction. The goal is to preprocess the dataset, apply more than 3 machine learning algorithms, perform exploratory data analysis, and achieve an accuracy and F-score of more than 65%. 

Libraries used:
- Numpy
- Pandas
- Sklearn
- Matplotlib

## Running the Jupiter File
- The code is implemented using Jupyter Notebook.
- Make sure you have Jupyter Notebook installed and running in your system.
- Clone the repository to your local machine.
- Open the Jupyter Notebook file (Heart_Attack_Prediction) and run the cells to see the output.

## Preprocessing
- Load the dataset into a pandas DataFrame
- Check for missing values and handle them appropriately (drop, fill, etc.)
- Convert categorical variables into numeric using one-hot encoding or label encoding
- Normalize/standardize the numeric variables if needed
- Split the dataset into training and testing sets

## Machine Learning
- Train and test more than three different machine learning models (e.g. Logistic Regression, KNN, Random Forest, SVM, etc.)
- Evaluate the performance of each model using metrics like accuracy, f-score, precision, recall, etc.
- Implement the majority voting concept by taking predicted labels from all classifiers and assigning the final label based on the majority vote

## Exploratory Data Analysis
- Plot various graphs to understand the data insights (e.g. histograms, scatter plots, box plots, etc.)
- Check for correlations between variables and the target label
- Check for class distribution

## Results
- Report the final accuracy, f-score, and other performance metrics of the majority voting model
- Compare the performance of all models and provide insights on why one performed better than the others
- Discuss the insights gained from Exploratory Data Analysis


