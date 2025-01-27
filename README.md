# Mini_Project

# Malware Detection Using Machine Learning

# Overview

This repository contains a machine learning project focused on malware detection using the Decision Tree algorithm. The project utilizes a dataset with features related to malware analysis to train and evaluate the model.

# Project Structure

malware_detection.ipynb: Jupyter Notebook containing the main code for the project.

MalwareDataSet.csv: Dataset file in CSV format containing features for malware analysis.

README.md: This file providing an overview of the project.

# Dataset

The dataset (MalwareDataSet.csv) contains various features related to malware analysis, including AddressOfEntryPoint, MajorLinkerVersion, MajorImageVersion, MajorOperatingSystemVersion, DllCharacteristics, SizeOfStackReserve, NumberOfSections, ResourceSize, and legitimate.


# Data Summary

Total Entries: 137,444

Safe Instances: 96,526

Malware Instances: 40,918

Model Training and Evaluation

The Decision Tree classifier is used for training and predicting malware instances. The model's performance is evaluated using metrics such as the confusion matrix, precision-recall curve, and ROC curve.

# Visualization

The project includes functions for visualizing the model's performance, including:

Confusion Matrix

Precision-Recall Curve

ROC Curve

# Results

Upon evaluation, the Decision Tree model achieves a success rate of approximately 98.81%.
