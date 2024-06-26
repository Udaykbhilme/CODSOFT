# Data Science Internship Project by CODSOFT

Welcome to the repository for my Data Science Internship project with CODSOFT! This project consists of three distinct tasks that cover a range of data science skills from data analysis to machine learning model building. Below, you’ll find a summary of each task, the datasets used, and the methodologies applied. This project is a great demonstration of practical data science skills using Python.

## Table of Contents

- [Project Overview](#project-overview)
- [Task 1: Titanic Survival Prediction](#task-1-titanic-survival-prediction)
- [Task 2: Movie Rating Prediction](#task-2-movie-rating-prediction)
- [Task 3: Iris Flower Classification](#task-3-iris-flower-classification)
- [Technologies Used](#technologies-used)

## Project Overview

This project comprises three data science tasks designed to build foundational skills in data preprocessing, exploratory data analysis, and machine learning. Each task uses a well-known dataset and focuses on different aspects of predictive modeling.

## Task 1: Titanic Survival Prediction

### Objective
Develop a machine learning model to predict whether a passenger on the Titanic survived based on features such as age, gender, ticket class, fare, and cabin information.

### Dataset
The dataset is derived from the [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic/data). It includes details about each passenger, including:
- Age
- Gender
- Ticket class
- Fare
- Cabin
- Survival status

### Methodology
- **Data Cleaning**: Handle missing values and outliers.
- **Exploratory Data Analysis (EDA)**: Identify patterns and relationships in the data.
- **Feature Engineering**: Create new features or modify existing ones to improve model performance.
- **Model Building**: Use classification algorithms such as Logistic Regression, Random Forest, and Support Vector Machines.
- **Evaluation**: Assess model performance using metrics like accuracy, precision, and recall.

### Files
- `Titanic_data.csv`: The dataset file.
- `task_1.ipynb`: Google collab containing data analysis and model building code.

## Task 2: Movie Rating Prediction

### Objective
Build a regression model to predict the rating of a movie based on its genre, director, and cast.

### Dataset
The dataset includes historical movie data with the following features:
- Genre
- Director
- Actors
- User/Critic Ratings

### Methodology
- **Data Preprocessing**: Clean the dataset and handle categorical variables.
- **EDA**: Analyze the relationship between different features and movie ratings.
- **Feature Engineering**: Encode categorical features and handle missing data.
- **Model Building**: Use regression techniques like Linear Regression, Ridge, and Lasso.
- **Evaluation**: Use metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

### Files
- `IMDb_Movies_India_data.csv`: The dataset file.
- task_2.ipynb`: Google collab with the data analysis and model development.

## Task 3: Iris Flower Classification

### Objective
Create a machine learning model to classify Iris flowers into three species (setosa, versicolor, virginica) based on their sepal and petal measurements.

### Dataset
The Iris dataset is a classic dataset available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris). It includes:
- Sepal length
- Sepal width
- Petal length
- Petal width
- Species (setosa, versicolor, virginica)

### Methodology
- **Data Analysis**: Visualize the data and understand the distribution of features.
- **Model Building**: Apply classification algorithms like Decision Trees, K-Nearest Neighbors, and Support Vector Machines.
- **Evaluation**: Evaluate the model using accuracy, confusion matrix, and F1-score.

### Files
- `IRIS_data.csv`: The dataset file.
- `task_3.ipynb`: Google collab containing the analysis and model building.

## Technologies Used

- **Python**
- **Google collab**
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for machine learning

