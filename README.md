# Lung-Guard-A-Hybrid-Ensemble-Model-for-Early-Lung-Disease-Classification

Lung Guard: A Hybrid Ensemble Model for Early Lung Disease Classification
This project builds a predictive model to assess the likelihood of lung cancer using a combination of classical machine learning algorithms and a deep learning model (TabNet). It involves data preprocessing, class balancing, model training, and evaluation to identify the most effective predictive strategy.

 Dataset
The dataset includes demographic and behavioral survey responses relevant to lung cancer diagnosis, such as:
* Age
* Gender
* Smoking History
* Alcohol Consumption
* Anxiety & Fatigue
* Shortness of Breath
* Other lifestyle and symptom-related attributes

 Objective
The goals of this project are to:
* Explore and analyze the dataset to understand feature distributions and correlations
* Preprocess data through encoding and scaling
* Balance class distribution using oversampling
* Train and compare multiple machine learning models
* Implement a TabNet deep learning model for tabular data
* Combine TabNet and Random Forest using an ensemble approach
* Evaluate all models using accuracy, precision, recall, and F1-score

 Models Used
* Random Forest Classifier
* TabNet Classifier
* Hybrid Ensemble (TabNet + Random Forest using Soft Voting)

 Results
The best-performing ensemble model achieved ~97% accuracy, with improved recall—a critical metric for medical prediction tasks.
