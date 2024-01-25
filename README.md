# Data Driven Model

## Predicting Disease Type Based on Biomarkers: An Analysis using the Therapeutic Target Database

This project aims to build a data driven model that predicts the type of disease based on the associated biomarkers. The analysis utilizes the Therapeutic Target Database, which contains comprehensive information on biomarkers and their relationships with various diseases.

## Dataset Description

The dataset used in this project is a subset called "Biomarker to disease mapping with ICD identifiers" from the Therapeutic Target Database. It comprises information on biomarkers, diseases, and their identification symbols. Biomarkers are specific biological characteristics that can serve as indicators of health or disease. The dataset includes biomarker identifiers, biomarker names, disease names, and disease identifiers based on the International Classification of Diseases (ICD).

[Dataset Source](https://db.idrblab.net/ttd/full-data-download)

## Objective

The objective of this analysis is to develop a model that can predict the type of disease based on the associated biomarkers. By accurately categorizing biomarkers with unique IDs into disease types, this model can potentially contribute to advancements in drug design, therapeutic interventions, and personalized medicine. However, the task is challenging due to the large number of different disease categories (167), which may affect the quality of the predictions.

## Models Used

- Sequential Neural Network
- KNeighbors Classifier
- SGD Classifier
- Naive Bayes
- SVC
- Linear SVC
- Random Forest Classifier

Please refer to the respective model implementations for more details.

Feel free to contribute or provide feedback to enhance the model's performance!
