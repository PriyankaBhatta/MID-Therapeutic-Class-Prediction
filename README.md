# MID-Therapeutic-Class-Prediction
Welcome to the MID Therapeutic Class Prediction project! This repository documents my work on analyzing the Medicines Information Dataset (MID) to build and analyze a Logistic Regression model.

## Overview

This project leverages a dataset comprising 192,807 rows from the Medicines Information Dataset (MID) to predict therapeutic classes—such as ANTI DIABETIC, ANTI INFECTIVES, and CARDIAC—using features including `HowToUse`, `ProductBenefits`, and `SideEffect`. The implemented Logistic Regression model delivers an impressive overall accuracy of ~98.2%, showcasing robust performance on major classes. However, it faces challenges with minor classes (e.g., OTHERS, STOMATOLOGICALS) due to limited sample sizes, highlighting areas for potential data augmentation.

## Project Structure

* Raw and processed dataset files from kaggle.

* Jupyter notebooks for EDA, model training, and analysis.

* Performance analysis, confusion matrix, visualizations, and video demo.

* Python scripts for data preprocessing and model evaluation.

## Key Findings

* Accuracy: ~98.2%
* Strong Classes: ANTI DIABETIC, ANTI INFECTIVES, CARDIAC, PAIN ANALGESICS, RESPIRATORY (precision/recall >0.95)
* Weak Classes: ANTI NEOPLASTIC (0.94/0.78), OTHERS/STOMATOLOGICALS/VACCINES (F1=0 due to low samples)
* Misclassifications: Occur between similar classes (e.g., GASTRO INTESTINA vs GASTRO INTESTINAL)

  
