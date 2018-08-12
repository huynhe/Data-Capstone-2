# Data-Capstone-2

This repository address the Home Credit Default Risk Kaggle Competition: https://www.kaggle.com/c/home-credit-default-risk
Please down the raw data from there if you would like to run the code found in the notebooks.

The repository contains multiple submissions for the reports to reflect 3 sets of submissions (Milestone 1, Milestone 2, and Final).

The deliverables for this project include 5 notebooks, "Capstone 2 Final Report.pdf", and "Capstone 2 Milestone Slides.pdf".

The first of the five notebooks is labeled "Feature Selection.ipynb". This notebook contains all the code for selecting the 
applicable features from a heterogenous pool of 300+ variables. The code works with 5 of the 7 provided datasets separately
to prepare it for cleaning and merging in the Data Wrangling notebook.

The second notebook is labeled "Data Wrangling.ipynb". This notebook contains the code for cleaning and merging the data
to prepare it for exploratory data analysis. Code for feature engineering was also included in this notebook.

The third notebook is labeled "Data Visualization and Inferential Statistics.ipynb". This is the largest notebook containing 
code to perform data visualizations and draw insights. It also contains code for inferential statistics to validate the 
application of variables in the deployment of the models. Some training data was transformed in this notebook.

The fourth notebook is labeled "Preparing the Test Data.ipynb". The purpose of this notebook was to replicate all the 
transformation steps performed on the training data for the test data. This involved the full set of feature selection,
data wrangling, and feature engineering.

The last notebook is labeled "Building the Model.ipynb". This notebook uses the final versions of the training and test data
for training and deployment of the model. A total of 5 different algorithms were trialed during the development of the model.
Multiple variations of the variables were also attempted to improve the accuracy of the model. 
