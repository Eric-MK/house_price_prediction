# California Housing Price Prediction
### Overview
The project focuses on predicting housing prices in California using a linear regression model. The dataset used is the California Housing dataset, which includes features like median income, house age, average number of rooms and bedrooms, population, and location coordinates (latitude and longitude).

### Dependencies
* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [scikit-learn](https://scikit-learn.org/)
 

### Dataset
The California Housing dataset is a well-known dataset used in machine learning and statistics for predicting housing prices. In this project, the dataset is accessed and downloaded through the scikit-learn library, a Python library widely used for machine learning.

Specifically, we use the fetch_california_housing function from scikit-learn's datasets module. This function automatically downloads the dataset from a remote repository, making it easy to access and use for our analysis and model building.

The dataset contains data about different housing blocks in California, including:

* MedInc: median income in block
* HouseAge: median house age in block
* AveRooms: average number of rooms per household
* AveBedrms: average number of bedrooms per household
* Population: block population
* AveOccup: average number of household members
* Latitude: block latitude
* Longitude: block longitude
* **Target variable:** Median house value for California districts
