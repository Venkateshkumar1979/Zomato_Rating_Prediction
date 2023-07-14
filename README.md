# Zomato_Rating_Prediction
Zomato-Bengaluru Rating Prediction using ML Algorithms 
The fundamental concept of analyzing the Zomato dataset is to get a reasonable idea of the factors influencing each restaurant’s aggregate ranking, setting up different types of restaurants at different locations. The main objective of this project is to perform extensive exploratory data analysis (EDA) on the Zomato dataset and build an appropriate machine learning model that will help various Zomato restaurants to predict their respective ratings based on certain features.
The following tasks have been performed

**Explore the Data**

•	Understanding each feature

→	'url' - contains the url of the restaurant in the zomato website

→	'address'- contains the address of the restaurant in Bengaluru
→	'name' - contains the name of the restaurant

→	'online_order' - whether online ordering is available in the restaurant or not

→	'book_table' - table book option available or not

→	'rate' - contains the overall rating of the restaurant out of 5

→	'votes' - contains total number of rating for the restaurant

→	'phone' - contains the phone number of the restaurant

→	'location' - contains the neighborhood in which the restaurant is located

→	'rest_type' - restaurant type

→	'dish_liked' - Most liked dishes in the restaurant

→	'cuisines' - Cuisines served by the restaurant

→	'approx_cost(for two people)' - Approximate cost for 2 persons

→	'reviews_list' - Reviews by the customers

→	'menu_item' - Menu list from the restaurant

→	'listed_in(type)' - Category of the restaurant

→	'listed_in(city)' - City where the restaurant is situated

•	Exploring the dataset info, describe and finding columns with categories, and numeric columns.

**Data Cleaning:**

•	Deleting redundant columns.

•	Renaming the columns.

•	Dropping duplicates.

•	Cleaning individual columns.

•	Remove the NaN values from the dataset

•	Check for some more Transformations

**Data Visualization:**

•	Restaurants delivering Online or not

•	Restaurants allowing table booking or not

•	Table booking Rate vs Rate

•	Best Location

•	Relation between Location and Rating

•	Restaurant Type

•	Gaussian Rest type and Rating

•	Types of Services

•	Relation between Type and Rating

•	Cost of Restaurant

•	No. of restaurants in a Location

•	Restaurant type

•	Most famous restaurant chains in Bengaluru

Appropriate features are selected to build an ML algorithm to predict the rating of a restaurant. 

Here are brief descriptions of algorithms used to build a model using various like Linear regression, Support vector regression, Random forest regression and extra trees regressor:

**Linear Regression:** Linear regression is a statistical method that is used to establish a relationship between a dependent variable and one or more independent variables. It assumes that there is a linear relationship between the dependent variable and the independent variables. The goal of linear regression is to find the best-fit line that describes the relationship between the variables.

**Support Vector Regression:** Support Vector Regression (SVR) is a type of regression analysis that uses support vector machines (SVMs) to predict continuous variables. It is similar to SVMs in classification problems but instead of predicting classes, it predicts continuous values. SVR tries to find the best hyperplane that maximizes the margin between the predicted values and the actual values.

**Random Forest Regression:** Random Forest Regression is an ensemble learning method for regression problems. It works by constructing multiple decision trees at training time and outputting the mean prediction of the individual trees as the final prediction. The random forest algorithm introduces randomness when building each tree to make them different from each other.

**Extra Trees Regressor**: Extra Trees Regressor is another ensemble learning method for regression problems. It works by constructing multiple decision trees at training time and outputting the mean prediction of the individual trees as the final prediction. The difference between Random Forest Regression and Extra Trees Regressor is that Extra Trees Regressor introduces more randomness when building each tree by selecting random thresholds for each feature.
