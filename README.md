# Titanic - Machine Learning from Disaster 

This repository contains a Machine Learning project that predicts passenger survival on the Titanic using passenger data (such as age, gender, socio-economic class, etc.). This is a classic challenge from the Kaggle Titanic competition.

##  Project Overview
* **Goal:** Predict whether a passenger survived or perished during the Titanic shipwreck.
* **Accuracy Achieved:** 
  * **Training Accuracy:** ~82.7%
  * **Testing Accuracy:** ~81.0%
* **Best Hyperparameters:** Selected via `GridSearchCV` (`learning_rate`: 1.0, `n_estimators`: 250).

## Technologies & Libraries Used
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:**
  * **Pandas & NumPy** (Data cleaning and preprocessing)
  * **Scikit-Learn** (Model training, grid search hyperparameter tuning, evaluation)
  * **Matplotlib & Seaborn** (Data visualization)

##  Repository Structure
* `Titanic_Survival_Prediction.ipynb` - The main Jupyter Notebook containing EDA, preprocessing, model training, and evaluation.
* `train.csv` - The training dataset with survival labels.
* `test.csv` - The test dataset (without survival labels).
* `gender_submission.csv` - A sample submission file representing the baseline model.
* `.gitignore` - Tells Git which files to ignore (like the virtual environment).

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/AbdelrahmanElsawy404/Titanic.git
   cd Titanic
