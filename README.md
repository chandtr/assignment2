#What drives the price of a car?

Exploration Data Analysis of the used cars information and finding the features which impact the car prices and creating the model for predicting the price of the cars


About data :
In this application, you will explore a dataset from Kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a car more or less expensive. As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.

Exploration :
This Exploration based on the Numerical and Categorical value comparision from the various Plots and statistical data.
Analyzed the dataset contains information on 426K cars to ensure speed of processing


After doing EDA on Numeric and categorial values, tried to find the top n highly correlated features. Tried with simple Linear regression, added the polynomial features with various hyperparameters for the model.

Went thru multiple iterations and found out the following features are creating the best model compare to other features, and Hyperparameter with degree=3,
'transmission_other', 'year', 'condition_good', 'drive_4wd', 'manufacturer_ram', 'cylinders_8 cylinders', 'paint_color_white', 'paint_color_black','drive_rwd', 'manufacturer_gmc','manufacturer_tesla', 'manufacturer_audi', 'manufacturer_jaguar', 'manufacturer_ford','manufacturer_alfa-romeo', 'manufacturer_rover', 'manufacturer_porsche'


Link to this notebook :
https://github.com/chandtr/assignment2/blob/master/prompt_II.ipynb
