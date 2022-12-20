# Spaceship-Titanic-Classification
This is the repository for the source code of the spaceship titanic prediction and analysis using machine learning methods project found on https://www.kaggle.com/competitions/spaceship-titanic You can find a notebook here as well https://www.kaggle.com/code/alinaageichik/basic-eda-finetuning-of-ml-models-and-ensemble  
## Dependencies (Anaconda):  

Scikit-learn 1.1.0 (`conda install -c conda-forge scikit-learn`)  

Scipy 1.8.1 (`conda install -c conda-forge scipy`)  

Numpy 1.23.1 (`conda install -c conda-forge numpy`)  

Matplotlib 3.5.2 (`conda install -c conda-forge matplotlib`)  

Seaborn 0.11.2 (`conda install -c conda-forge seaborn`)  

Pandas 1.4.3 (`conda install -c conda-forge pandas`)    

XGBoost 1.7.1 (`conda install -c conda-forge xgboost`)  

LightGBM 3.3.3 (`conda install -c conda-forge lightgbm`) 

This project is implemented using Python 3.8.5.

## Results:  

| Model | Validation Accuracy (%) | 
| --- | --- |  
| Random Forest | 82.00 |
| Perceptron | 72.52 |  
| Support Vector Machines | 78.30 | 
| Linear Support Vector Machines | 79.03 | 
| K-Nearest-Neighbours | 79.66 | 
| Stochastic Gradient Descent | 79.06 | 
| Decision Tree | 92.87 | 
| Gaussian Naive Bayes | 69.09 | 
| Logistic Regression | 79.13 |
| Multi-layer Perceptron | 80.60 |
| Gradient Boosting | 80.75 |
| LightGBM | 82.08 |
| XGBoost | 81.59 |
| Quadratic Discriminant Analysis | 71.02 |
| Linear Discriminant Analysis | 76.69 |
| Ensemble (LGBM + DT + XGB + GB + RF ) | 86.49 |

Prediction (submission) accuracy in Kaggle is 79.30%.
