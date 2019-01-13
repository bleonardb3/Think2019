# Think 2019 Session #3259  
## Hands On Lab: Introduction to Data Science using IBM Watson Studio. 

## Description:

Work with IBM's Watson Studio in this workshop to build, train, and test machine learning/deep learning models. Participants will be led through the following three hands-on labs: 

1. [Lab-1](Lab-1) - The first lab will use Jupyter Notebooks and the XGBoost library to apply machine learning to a classification problem in the healthcare profession. The Watson Machine Learning API will then be used to save and deploy the model. 
1. [Lab-2](Lab-2) - The second lab will demonstrate Watson Machine Learning capabilites to simplify the building and deployment of machine learning models. The ability to monitor and adjust the deployed model will be demonstrated via the continuous learning capability of Watson Studio. 
1. [Lab-3](Lab-3) - The third lab will feature the new Watson Studio Neural Network modeler, and Experiment Assistant to build, train, and test a Convolutional Neural Network to classify images.  

## Instructions: Create a Watson Studio project and set up the required services. 

### Step 1.  Log into your Watson Studio account at datascience.ibm.com, then select `View All Projects`.

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Select%20View%20All%20Projects.png"/>

### Step 2.  If you have an existing project from following the signup instructions then select it, and skip to Step 8.  Otherwise, click on `New Project`. 
> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Select%20New%20Project.png"/>

### Step 3. Enter the project name (eg. Watson Studio Labs), optionally a description, and then click on `Add` in the Storage section. Note if you have already provisioned cloud object storage (you shouldn't see an Add button) , then just click on the `Create` button, and skip to Step 8. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/New%20Project%20Panel%20-%20Add%20Storage.png"/>

### Step 4. Click on the Lite plan, and then click on `Create`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Create%20Object%20Storage.png"/>

### Step 5. Optionally change the storage name, and then click on `Confirm`

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Confirm%20Creation.png"/>

### Step 6. Click on `Refresh`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Click%20Refresh.png"/>

### Step 7.  The cloud object storage should appear. Now click on `Create`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Click%20Project%20Create.png"/>

### Step 8. 

The labs in this Proof of Technology will require the following services to be created and associated with your project. 
1. Object Storage
1. Watson Machine Learning
1. Apache Spark  

The Object Storage service instance should already exist, having been created when the Watson Studio Labs (or whatever you named it) project was created. Both the Watson Machine Learning service, and the Apache Spark service need to be created and then associated with the project.  

### Step 9.  Click on the project `Settings` tab.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Settings.png"/>

### Step 10. Scroll down to `Associated Services`, then select `Add service` and select `Watson`.

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/SelectWatsonService.png"/>

### Step 11. Select the `Machine Learning` service 

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/SelectMachineLearningService.png"/>

### Step 12. Select `New`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20New%20Service.png"/>

### Step 13. Select the `Lite` plan. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Lite%20ML.png"/>

### Step 13. Scroll down and click `Create`, then change the `Service name` to `Machine Learning` in the `Confirm Creation` panel and click `Confirm`.  

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/ConfirmMachineLearningCreation.png"/>

### Step 14. The Machine Learning service that you created should now appear in `Associated Services`. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/See%20ML%20in%20Associated%20Services..png"/>

### Step 15. Follow the same process as in steps 10-14, except this time add a Spark service. 
