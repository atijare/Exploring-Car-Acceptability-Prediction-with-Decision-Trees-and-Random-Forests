## Car Acceptability Prediction Using Machine Learning ##
Project Overview

This project predicts the acceptability of cars based on features such as buying price, maintenance cost, number of doors, passenger capacity, luggage boot size, and safety. Using the Car Evaluation dataset, I trained Decision Tree and Random Forest classifiers to classify cars as:

unacc (unacceptable)
acc (acceptable)
good
vgood (very good)

The project demonstrates how machine learning can be applied to categorical data and provides insights into which car features are most influential in consumer decision-making.
Features

Data Preprocessing: Encoding categorical features, train-test split.
Exploratory Data Analysis (EDA): Visualizations to explore feature distributions and their relationship with car acceptability.
Model Training & Evaluation: Decision Tree and Random Forest with metrics including accuracy, classification report, and confusion matrices.
Feature Importance Analysis: Identify which attributes (like safety and price) most impact car acceptability.
Insights & Discussion: Interpret results and highlight key takeaways for real-world decision-making.

Technologies Used:
Python
Pandas
Scikit-learn
Matplotlib & Seaborn

How to Run
Clone the repository:
git clone <your-repo-url>

Install dependencies: pip install pandas scikit-learn matplotlib seaborn

Open the Jupyter Notebook (.ipynb) and run all cells.
Dataset: The dataset is the Car Evaluation dataset from the UCI Machine Learning Repository. It contains categorical features describing car attributes and a target variable indicating car acceptability.
Dataset link: UCI Car Evaluation Dataset

Results & Insights
Random Forest performed slightly better than Decision Tree in accuracy.
Safety and buying price are the most important features in predicting car acceptability.
Visualizations provide clear evidence of how different features influence consumer decisions.

License
This project is open-source and free to use under the MIT License.
