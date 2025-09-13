# Titanic Project

## Overview
This project analyzes the Titanic dataset using Python. The goal is to understand passenger data, handle missing values, and visualize key insights.

## Dataset
The dataset used is `titanic.csv` and includes columns such as PassengerId, Name, Age, Sex, Pclass, SibSp, Parch, Ticket, Fare, Cabin, Embarked, Survived.

## Project Steps
1. Import Libraries: pandas, numpy, matplotlib, seaborn
2. Load Dataset: df = pd.read_csv("titanic.csv")
3. Data Cleaning: Fill missing Age with median, Embarked with mode, drop Cabin column
4. Data Exploration: Count survived vs non-survived, visualize Age and Fare distributions
5. Conclusions: Summary of findings and insights

## How to Run
Open `titanic_project.ipynb` in Jupyter Notebook and run each cell sequentially. Ensure `titanic.csv` is in the same folder as the notebook.

## Author
Walaa Mohamed
