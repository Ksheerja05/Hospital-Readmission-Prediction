# Hospital Readmission Prediction

## Overview
This project is based on predicting whether a patient will be re-admitted to the hospital based on their medical history.

## File Structure
1. hspt_readmission.ipynb: Main Python script for sentiment analysis, data preprocessing, model training, and visualization.
2. hospital_readmissions.csv: Sample dataset containing patients' medical history. The data was taken from Kaggle- https://www.kaggle.com/datasets/dubradave/hospital-readmissions/data
3. README.md: Project README file.

## Nature and Characteristics of the Dataset
The dataset used in this project consists of customer reviews from an online fashion retailer. It includes 23486 rows and 10 feature variables:

1. "age" - age bracket of the patient
2. "time_in_hospital" - days (from 1 to 14)
3. "n_procedures" - number of procedures performed during the hospital stay
4. "n_lab_procedures" - number of laboratory procedures performed during the hospital stay
5. "n_medications" - number of medications administered during the hospital stay
6. "n_outpatient" - number of outpatient visits in the year before a hospital stay
7. "n_inpatient" - number of inpatient visits in the year before the hospital stay
8. "n_emergency" - number of visits to the emergency room in the year before the hospital stay
9. "medical_specialty" - the specialty of the admitting physician
10. "diag_1" - primary diagnosis (Circulatory, Respiratory, Digestive, etc.)
11. "diag_2" - secondary diagnosis
12. "diag_3" - additional secondary diagnosis
13. "glucose_test" - whether the glucose serum came out as high (> 200), normal, or not performed
14. "A1Ctest" - whether the A1C level of the patient came out as high (> 7%), normal, or not performed
15. "change" - whether there was a change in the diabetes medication ('yes' or 'no')
16. "diabetes_med" - whether a diabetes medication was prescribed ('yes' or 'no')
17. "readmitted" - if the patient was readmitted at the hospital ('yes' or 'no')

## Data Preprocessing Steps
1. Handling Missing Values.
2. Converting categorical data to numerical data.

## Model Architecture and Development Process
Random Forest Classifier was used.

## Evaluation Metrics and Results
1. Training Accuracy: Achieved 100% accuracy on the training set.
2. Test Accuracy: Test accuracy was around 99%.
3. This indicaties overfitting.

## Visualizations and Their Interpretations
EDA was performed on the dataset. Correlation matrix, heatmaps and bar charts are shown in the python file.

## Conclusion:
The model is overfitting as the test accuracy is 100%.
We can prevent overfitting by:
1. Reducing tree depth.
2. Using more data.
3. Hyperparameter tuning.
Due to time constraints, I was unable to put these suggestions into practice, but I will ultimately work on them and enhance the model's performance.
