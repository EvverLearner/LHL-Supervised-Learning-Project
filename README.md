# machine_learning_project-supervised-learning

## Project/Goals
This project is an exercise in supervised learning on a dataset about diabetes diagnoses and associated health information, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases. The goal is to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements. This project uses Random Forest and SVM models to attempt this.

## Process
1. Performed EDA on the dataset, to determine initial correlations and trends that can be used to fulfill the project goal.
2. After EDA, preprocessing and feature selection/engineering is performed.
3. For model construction, I began with a Random Forest model. This allowed me to determine the most impactful features.
4. Random Forest model was done again, this time using impactful features from the initial iteration.
5. Using the most impactful features found by the Random Forest, they were used in the second model which was SVM.
6. Results of the models were interpreted and compared, especially F1 and AUC-ROC scores.

## Results
Glucose levels in blood, BMI, and Age appeared to be the top 3 predictors for a diabetes diagnosis. The SVM model was more accurate on the testing data, at 78.4% accuracy score. However, the AUC-ROC and F1 scores of both models were high enough to be confident in a correct diagnosis (whether positive or negative) predicted by the models.

## Challenges 
1. Performing sufficient EDA and preprocessing to have effective models.
2. Maximizing model accuracy without biasing or misrepresenting the data in the models.

## Future Goals
1. Use hyperparameter tuning and cross validation methods to explore results further, and potentially craft a stronger model.
2. Build different models that may be more effective for binary classification.

