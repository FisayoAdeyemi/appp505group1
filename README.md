# README

## Overview

This document accompanies the submission of the predictive analytics project focusing on energy analysis of residential buildings in British Columbia (BC). The project leverages machine learning techniques to predict the Energy Utilization Index (EUI) to assist stakeholders in enhancing energy efficiency, complying with the Carbon Tax, and reducing costs.

## Steps to Replicate results

1. Open the Tablue Prep packaged flow titled "Team 1 - Predictive Analytics Flow"
2. Change the output step to any desired local location on your laptop (e.g downloads or desktop) - after this step, you will have a local version of the file we used to train the model
3. Note: We have uploaded the cleaned training data on Github already at [Online Github Repo](https://raw.githubusercontent.com/FisayoAdeyemi/appp505group1/main/EUI.csv) and you do not necessarily need to carry out step 1 and 2.
4. Access the project notebook at [Google Colab](https://colab.research.google.com/drive/1WWSN2qqrSPPaymx6dwAWJchS4nZk2SQY?usp=sharing). This notebook contains all the code and visualization pertinent to the predictive models developed during the study.
5. Click "Run All" or use the shortcut CMD/Ctrl + F9 to run all cells
6. Wait for about 3-5 minutes and the scroll down for resukts
  

## Contents

- `Predictive Analytics Report`: A detailed report on the analysis performed, including problem definition, data handling, and objectives.
- `Google Colab Notebook`: A computational notebook where all the data preprocessing, model training, and evaluations are performed.

## Google Colab Notebook

Access the project notebook at [Google Colab](https://colab.research.google.com/drive/1WWSN2qqrSPPaymx6dwAWJchS4nZk2SQY?usp=sharing). This notebook contains all the code and visualization pertinent to the predictive models developed during the study.

## Dataset

The dataset used for this project is sourced from an Official Local Government Entity in BC, containing information on approximately 750 buildings over five years across five regions. The dataset includes:

- Region
- Consumption (ekWh)
- Floor area (ft²)
- EUI (kW/ft²)
- Emission (tCO2e)
- Emissions per Floor Area (KgCO2e/sq. ft)
- Reporting Year

Data has been anonymized to comply with privacy laws and ethical standards.



## Machine Learning Models

Multiple models were developed and cross-validated, including:

- Linear Regression
- Decision Tree
- Random Forest
- Bagging
- AdaBoost
- Gradient Boosting
- Deep Neural Network

Gradient Boosting achieved the highest R2 score and the lowest RMSE, indicating its superior predictive accuracy among the tested models.

## Tools and Libraries

- Tableau Prep for data preprocessing
- Scikit-learn for implementing machine learning algorithms
- Pandas and NumPy for data manipulation
- Matplotlib and Seaborn for data visualization

## References

1. ENERGY STAR: [Understanding Metrics](https://www.energystar.gov/buildings/benchmark/understand-metrics/what-eui)
2. Government of Canada - Energy Market Analysis: [Provincial and Territorial Energy Profiles - British Columbia](https://www.cer-rec.gc.ca/en/data-analysis/energy-markets/provincial-territorial-energy-profiles/provincial-territorial-energy-profiles-british-columbia.html)
3. Scikit-Learn Documentation for Gradient Boosting Classifier: [GradientBoostingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)
