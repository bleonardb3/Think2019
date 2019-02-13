# Lab-1 - Train and deploy a heart disease prediction model using XGBoost and IBM Watson Machine Learning APIs

## Introduction:

In this lab, you will use a Jupyter Notebook to train a model using the XGBoost library to classify whether a person has heart disease or not In addition to training a model, the notebook also explains how to persist a trained model to the IBM Watson Machine Learning repository, and deploy the model as a REST service.

In order to train and test the heart disease prediction model, you will be using an open source data set published in the University of California, Irvine (UCI) Machine Learning Repository.

The notebook uses Python 3.5 runtime, XGBoost 0.6 and Scikit-Learn 0.17.

## Objectives:

Upon completing the lab, you will know how to:

1. Load a CSV file into Pandas DataFrame.
1. Data exploration using Pixiedust
1. Prepare data for training and evaluation.
1. Create, train, and evaluate a XGBoost model.  
1. Visualize the importance of features that were used to train the model.
1. Use cross validation to select optimal model hyperparameters based on a parameter grid
1. Persist best model in Watson Machine Learning repository using Python client library.
1. Deploy the model for online scoring using the Watson Machine Learning's REST APIs


## Instructions:

### Step 1.  Click on the hamburger icon, then `Projects`, and then `View All Projects`
> <img src="https://github.com/bleonardb3/DS_POT_02-07/blob/master/images/Navigation%20Selection.png"/>
> <img src="https://github.com/bleonardb3/DS_POT_02-07/blob/master/images/ViewAllProjects.png"/>


### Step 2.  Select the project you created at the beginning of this proof of technology.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Watson%20Studio%20Labs.png"/>

### Step 3.  We are now going to create a new notebook in our project. This notebook will be created from a url that points to the Heart Disease notebook in the github repository. Click the `Add to project` link and then the `Notebook` link as shown below. 

> <img src="https://github.com/bleonardb3/Think2019/blob/master/Lab-1/images/AddToProject.png"/>

### Step 4.  Create the notebook.

> <img src="https://github.com/bleonardb3/Think2019/blob/master/Lab-1/images/NewNotebook.png"/>

1. Click the `From URL` tab under `New Notebook`.
1. Give the notebook a name in the `Name` field, for example `Heart Disease` and optionally you can give it a description.
1. In the Notebook URL field, use `https://github.com/bleonardb3/Think2019/blob/master/Lab-1/Heart%20Disease.ipynb`.
1. Make sure to change the default environment to the `Default Spark Python 3.5 XS environment.` 

### Step 5.  Follow the instructions in the notebook.




