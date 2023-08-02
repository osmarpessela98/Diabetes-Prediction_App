# Diabetes Prediction App 

A Web App to predict the onset of diabetes based on diagnostic measures. 

App is deployed in Heroku, click the link to access it : [Open in Heroku](https://ToDeploy/)


## Data

The data for the following example is originally from the [National Institute of Diabetes and Digestive and Kidney Diseases](https://www.niddk.nih.gov/) and is [available on Kaggle.](https://www.kaggle.com/uciml/pima-indians-diabetes-database) The data contains information on females at least 21 years old of Pima Indian heritage.
Since the data has been added to the `data/` directory, cloning this repository would suffice.

## Pre-requisites

The project was developed using python 3.8.3 with the following packages.
- Pandas
- Numpy
- Scikit-learn
- Pandas-profiling
- Joblib
- Streamlit

Installation with pip:

```bash
pip install -r requirements.txt
```

## Getting Started
Open the terminal in you machine and run the following command to access the web application in your localhost.
```bash
streamlit run app.py
```

## Files
- notebook/Prima_Indians_Diabetes_Prediction.ipynb : Jupyter Notebook with all the workings including pre-processing, modelling and inference.
- app.py : Streamlit App script
- requirements.txt : pre-requiste libraries for the project
- models/ : trained model and scaler objects
- data/ : source data
- setup.sh : Setup file for Heroku.
- Procfile : To trigger the app in Heroku.

## Summary
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
All patients here are females at least 21 years old of Pima Indian heritage. The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
Business Goal - To build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes?


## Acknowledgements

[Kaggle](https://kaggle.com/), for providing the data for this problem statement.