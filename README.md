# Biomarker Classification Project
# Project Description:

This project focuses on classifying cancer biomarkers using various machine learning algorithms, including Support Vector Machine (SVM), Decision Tree, Random Forest, K-Nearest Neighbors (KNN), Logistic Regression, and Naive Bayes. The goal is to accurately predict the type of biomarker based on a set of molecular properties such as molecular weight, stability, specificity, and various cancer marker levels.

# Special Thanks
A special thanks to Dr. Krishna Mohan from Srujana Cancer Hospitals, Hyderabad for his invaluable guidance and expertise in the field of cancer biomarkers, which greatly contributed to the development of this project.


Note: This project is still a work in progress, and more features and optimizations are planned.

# Table of Contents
Installation
Usage
Models Used
Current Status
Future Work
Contribution

Installation
Clone the repository:
git clone https://github.com/yourusername/biomarker-classification.git
cd biomarker-classification
Install the required dependencies:

pip install -r requirements.txt
Add the dataset file biomarker_classification_final.xlsx to the /content/drive/MyDrive/ directory.

Usage
Run the main Python script to train and test the models:

python sparktank.py
The script will load the dataset, handle missing values, and split the data into training and testing sets. It will then fit multiple models and output the accuracy of each model

# Models Used
The following machine learning models have been implemented in this project:

Support Vector Machine (SVM)
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Logistic Regression
Naive Bayes

# Current Status
Data pre-processing is complete.
Initial implementation of multiple classification algorithms has been done.
Performance metrics such as accuracy are being calculated for each model.
The project is still in development, with future improvements planned.

# Future Work
Implement hyperparameter tuning for improved accuracy.
Add more advanced machine learning models.
Explore deep learning approaches to classification.
Optimize the model training and testing process.
Improve the handling of missing or inconsistent data.

#Contributing:
This project is being developed by a team of five members.
I am the 3rd team member, responsible for data pre-processing, including handling missing values, splitting the data, and preparing the dataset for model training and testing.

# References
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6436208/pdf/13048_2019_Article_503.pdf
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9569881/pdf/ijms-23-12041.pdf
# Sites
https://biomarkerres.biomedcentral.com/
