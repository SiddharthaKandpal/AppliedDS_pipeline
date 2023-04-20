# Creating Pipeline using Pycaret  
## OVERVIEW  
This pipeline project uses PyCaret, a machine learning library in Python, to train and evaluate two classification models on the penguins dataset from the Seaborn library. The goal of this project is to demonstrate how to use PyCaret to build and evaluate machine learning pipelines quickly and efficiently.  
Overall, this project showcases how PyCaret can simplify the machine learning pipeline creation process by providing a high-level API for data preprocessing, model training, hyperparameter tuning, ensembling, and evaluation.  
## SCOPE  
- Demonstrate the use of PyCaret, a machine learning library in Python, for building and evaluating a classification model on the penguins dataset.
- Train two classification models (logistic regression and random forest) using PyCaret's `create_model()` and `tune_model()` functions.
- Evaluate the performance of the trained models using PyCaret's `evaluate_model()` function.
- Ensemble the trained models using PyCaret's `blend_models()` function to create an ensemble model.
- Evaluate the performance of the ensemble model using PyCaret's `plot_model()` function.
- Use the trained ensemble model to make predictions on new data using PyCaret's `predict_model()` function.
- Provide a comprehensive example of a machine learning pipeline that includes data preparation, model training, hyperparameter tuning, model evaluation, and prediction.  
## TECHNOLOGIES USED  
[.pycaret](https://pycaret.org/)  
[.seaborn](https://seaborn.pydata.org/installing.html)
## DATASET  
This pipeline project uses PyCaret, a machine learning library in Python, to train and evaluate two classification models on the penguins dataset from the Seaborn library, which contains information about the physical characteristics of different types of penguins.  
Original Source- https://allisonhorst.github.io/palmerpenguins/   
## STEPS  
The pipeline consists of the following steps:

1. Import the Seaborn library and load the penguins dataset.
2. Import PyCaret's classification module and initialize PyCaret by calling the `setup()` function with the penguins dataset and specifying the target variable to be predicted (`species`).
3. Train and tune a logistic regression classifier using PyCaret's `create_model()` and `tune_model()` functions.
4. Train a random forest classifier using PyCaret's `create_model()` function.
5. Ensemble the logistic regression and random forest models using PyCaret's `blend_models()` function.
6. Visualize the trained ensemble model using PyCaret's `plot_model()` function.
7. Make predictions on new data by creating a new dataset consisting of the first 10 rows of the penguins dataset with the target variable removed and calling PyCaret's `predict_model()` function with the trained ensemble model and the new dataset as parameters.  
## DOCUMENTATION  
[.ipynb file to test run] ()  
## IMAGES  
![image](https://user-images.githubusercontent.com/78250442/233314271-21b96353-368d-4b1b-aec1-96ec4c897d0a.png)  
![image](https://user-images.githubusercontent.com/78250442/233314423-c5e13252-d98f-4d6a-a54a-53070e484b09.png)  
![image](https://user-images.githubusercontent.com/78250442/233314781-71762c0e-cfca-426b-9e7c-17297d81e3cd.png)  
![image](https://user-images.githubusercontent.com/78250442/233314904-4d459232-6895-4c7c-a9ad-12c784b74f9e.png)
![image](https://user-images.githubusercontent.com/78250442/233315067-ec3564bd-8036-49bb-b6c0-e1e8feed614a.png)
![image](https://user-images.githubusercontent.com/78250442/233315176-52d0fca1-ceb3-4d57-944e-996dd0e6c329.png)


