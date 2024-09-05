## Machine Failure Prediction - README

# Overview

This project focuses on Machine Failure Prediction by analyzing various independent failure modes. The machine failure prediction model helps businesses that rely on machinery to prevent downtime by identifying potential failures before they occur. The project leverages several machine learning models to predict failures based on multiple failure modes.

# Failure Modes

The machine failure is determined based on the following five independent failure modes:

	1.	Tool Wear Failure (TWF): Failure due to tool wear.
	2.	Heat Dissipation Failure (HDF): Failure due to inadequate heat dissipation.
	3.	Power Failure (PWF): Failure due to power loss or fluctuation.
	4.	Overstrain Failure (OSF): Failure caused by excessive strain on the machine.

If any of these failure modes are detected, the machine failure label is set to 1 (i.e., machine failure).

# Objective

The goal of this project is to predict machine failure by analyzing the above failure modes using machine learning models. By implementing predictive analytics, businesses can:

	•	Proactively detect failures before they occur.
	•	Reduce costly downtime due to unexpected machine failures.
	•	Optimize maintenance schedules and improve overall productivity.

# Machine Learning Models

Several machine learning models are used to classify whether a machine will fail or not:

	1.	Logistic Regression: A statistical model used for binary classification of machine failure.
	2.	Random Forest: An ensemble learning method that builds multiple decision trees and combines their outputs to improve accuracy.
	3.	Decision Tree: A model that uses a tree-like structure for decision-making based on feature values.
	4.	Support Vector Machine (SVM): A supervised learning model used for binary classification, separating data points with a hyperplane.

# Dataset

The dataset includes the following features:

	•	Failure modes: TWF, HDF, PWF, OSF
	•	Target label: Machine failure (1 for failure, 0 for no failure)

The dataset is used to train and test the machine learning models to predict whether a machine will fail based on the input failure modes.