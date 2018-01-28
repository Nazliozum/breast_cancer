# Objective

This project is prepared as part of an assignment for "DSCI 573: Feature and Model Selection" course in the Master of Data Science program at the University of British Columbia. Throughout the project, I identify a dataset, conduct exploratory data analysis, fit a machine learning model and apply various feature selection methods.

# Data

The data comes from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php) and links features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass to whether the mass is malignant or benign. The dataset can be downloaded [here](http://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data).

- There are 32 attributes in the dataset including **ID**, **diagnosis** (target variable) and **30 real-valued features** (input variables).


- Target variable has 2 values: 
    - M = malignant
    - B = benign


- The input variables consist of the mean, standard error, and "worst" or largest (mean of the three largest values) of the 10 characteristics of the cell nuclei present in each image, resulting in 30 features in total. The 10 characteristics are as follows:

```
    a) radius (mean of distances from center to points on the perimeter)
	b) texture (standard deviation of gray-scale values)
	c) perimeter
	d) area
	e) smoothness (local variation in radius lengths)
	f) compactness (perimeter^2 / area - 1.0)
	g) concavity (severity of concave portions of the contour)
	h) concave points (number of concave portions of the contour)
	i) symmetry 
	j) fractal dimension ("coastline approximation" - 1)
```

- The dataset consists of 569 observations:
    - 357 belonging to benign class
    - 212 belonging to malignant class.
    
- There are no missing values in the dataset.

More information on the dataset: [Wisconsin Diagnostic Breast Cancer (WDBC)](http://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.names)