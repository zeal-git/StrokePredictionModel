# StrokePredictionModel
This project aims to predict the probability of stroke in individuals using various health features provided in the dataset. The prediction model is based on data collected from Kaggle. The dataset contains factors such as age, gender, marital status, smoking status, hypertension, heart disease, and more. A machine learning model(such as Linear Regression, Random Forest, or GridSearchCV) is trained to predict the probability of stroke. 

TOOLS AND LIBRARIES USED:

1) PYTHON: The project is implemented using python.

2) numpy: for numerical computation
   pandas: for data manipulation
   matplotlib and seaborn: for data visualization
   scikit-learn: for building, training model 

3) jupyter lab: for development and analysis


ACKNOWLEDGMENTS: 

DATASET: healthcare-dataset-stroke-data.csv(316.97 kB)

Thanks to Kaggle community for providing valuable dataset. 

INSIGHTS:

Used Linear Regression Model to find the relationship between the age group prone to stroke through stated features in dataset. Through this model, I predicted an accuracy score of how well my model is predicting, which turned out to be 63% with the use of Random Forest regression. With further estimation using GridSearchCV for hyperparameter tuning, the accuracy score turned out to be 65%. 

