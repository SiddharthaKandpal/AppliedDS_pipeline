# Creating piepline using scikit-learn, pandas, Seaborn, Yellowbrick  
## OVERVIEW  
* The project involves building a machine learning pipeline for classifying penguin species based on physical characteristics.
* The pipeline uses scikit-learn, pandas, Seaborn, and Yellowbrick libraries.
* The data is preprocessed using a ColumnTransformer that applies different transformations to numerical and categorical features.
* The logistic regression model is used to predict the probability of each class based on the input features.
* The model is fit to the training data using scikit-learn's fit method and makes predictions on the testing data using scikit-learn's predict method.
* The performance of the model is evaluated using Yellowbrick's ConfusionMatrix.

## SCOPE  
* The scope of the project is to build a machine learning pipeline for classification tasks.

* The pipeline includes several important steps such as data preprocessing, model building, and model evaluation.
* The project uses scikit-learn, pandas, Seaborn, and Yellowbrick libraries for data manipulation, model building, and visualization.
* The pipeline can be used as a template for similar classification tasks on other datasets.  
## DATA  
The project specifically focuses on the popular "penguins" dataset via seaborn lib, which contains information about penguin species and their physical characteristics.  
Original Source- https://allisonhorst.github.io/palmerpenguins/  
## TECHNOLOGIES USED  
[.seaborn](https://seaborn.pydata.org/)  
[.scikit](https://scikit-learn.org/stable/install.html)  
[.yellowbrick](https://anaconda.org/DistrictDataLabs/yellowbrick)  
[.pandas](https://pandas.pydata.org/)  
## STEPS  
Here's a step-by-step plan used to create this pipeline:

1. Import the necessary libraries: scikit-learn, pandas, Seaborn, and Yellowbrick.
2. Load the penguins dataset using Seaborn's built-in function.
3. Preprocess the data using a `ColumnTransformer` to apply different transformations to numerical and categorical features separately:
   - Handle missing values in the dataset using scikit-learn's `SimpleImputer` class.
   - Scale the numerical features using scikit-learn's `StandardScaler` class.
   - Encode the categorical features using one-hot encoding using scikit-learn's `OneHotEncoder` class.
4. Split the preprocessed data into training and testing sets using scikit-learn's `train_test_split` function.
5. Build a logistic regression model using scikit-learn's `LogisticRegression` estimator.
6. Fit the model to the training data using the `fit` method.
7. Make predictions on the testing data using the `predict` method.
8. Evaluate the performance of the model using Yellowbrick's `ConfusionMatrix` visualization:
   - Instantiate the `ConfusionMatrix` object.
   - Fit the object to the testing data using the `fit` method.
   - Visualize the confusion matrix using the `poof` method.  
 ## DOCUMENTATION  
 [.ipynb file for test run](https://github.com/SiddharthaKandpal/AppliedDS_pipeline/blob/main/multiple_pipelines/Multiple_pipelines.ipynb)  
 ## IMAGE  
 ![image](https://user-images.githubusercontent.com/78250442/233328940-f9537d40-e4c2-4f73-8594-043f2e9ea25c.png)

