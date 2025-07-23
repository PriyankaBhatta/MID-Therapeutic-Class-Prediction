# MID-Therapeutic-Class-Prediction
Welcome to the MID Therapeutic Class Prediction project! This repository documents my work on analyzing the Medicines Information Dataset (MID) to build and analyze a Logistic Regression model.

Overview

This project uses a dataset with 192,807 rows to predict therapeutic classes (e.g., ANTI DIABETIC, ANTI INFECTIVES) based on features like HowToUse, ProductBenefits, and SideEffect. The Logistic Regression model achieved an overall accuracy of ~98.2%, with strong performance on major classes and weaker results on minor classes due to limited data.

Project Structure





data/: Raw and processed dataset files.



notebooks/: Jupyter notebooks for EDA, model training, and analysis.



reports/: Performance analysis, confusion matrix, visualizations, and video demo.



src/: Python scripts for data preprocessing and model evaluation.

Key Findings





Accuracy: ~98.2%



Strong Classes: ANTI DIABETIC, ANTI INFECTIVES, CARDIAC, PAIN ANALGESICS, RESPIRATORY (precision/recall >0.95)



Weak Classes: ANTI NEOPLASTIC (0.94/0.78), OTHERS/STOMATOLOGICALS/VACCINES (F1=0 due to low samples)



Misclassifications: Occur between similar classes (e.g., GASTRO INTESTINA vs GASTRO INTESTINAL)
