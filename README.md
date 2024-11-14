# Project Statement
A refined machine learning-based Pakistani Terrorism groups predictor, built on an enhanced ensemble model inspired by research, featuring an interactive Streamlit app and Dockerized deployment.


# Terrorism Group Predictor
This repository contains an implementation of a Terrorism Group Predictor based on a research paper that applies machine learning to classify and predict the responsible group behind terrorist incidents. The original research paper proposed a majority voting ensemble model using four classifiers: Naive Bayes, K-Nearest Neighbors (KNN), ID3 Decision Tree, and Decision Stump. This implementation enhances the original approach by adding a Random Forest classifier to the ensemble, improving predictive performance and model robustness.

# Project Overview
This project uses Streamlit to create an interactive web application that enables users to predict the responsible terrorist group based on specific incident features, such as:

Province/State
Attack Type
Target Type
Weapon Type

# Research Paper Reference
The original methodology and ensemble approach were inspired by the research paper titled:

"Terrorist Group Prediction Using Data Classification"

Credits to the authors of the research paper for their foundational work on this problem. This implementation builds upon their approach, adding refinements to the model and an additional classifier for improved accuracy.

# Features
## Machine Learning Model: Majority voting ensemble with five classifiers (Naive Bayes, K-Nearest Neighbors, ID3 Decision Tree, Decision Stump, and Random Forest).
## Streamlit Frontend: Interactive web application for user-friendly prediction and data visualization.
## Dockerized Deployment: Docker setup for easy containerization and deployment.
