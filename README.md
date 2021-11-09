# Capstone Project

The dataset that will be worked on is the estimation of obesity levels in individuals from the countries of Mexico, Peru and Colombia, based on their eating habits and physical condition supplied by UCI: https://archive.ics.uci.edu/ml/datasets/Estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition+

# Current Tentative Stages of Work:

## 1. Descriptive Statistics, Simple Exploration and Data Cleaning
 - Descriptive Statistics of all features for a general insight of the dataset
 - Exploring null values and duplicates and removing them.
 - Exploring Outliers (univariate & bivariate) and removing them if needed (quantitative)
## 2. Deep Data Exploration and Preparation for Cluster Analysis
 - Exploring correlation of all quantitative features
 - Create BMI feature based on formula and compare to class label for accuracy
 - Exploring misrepresentation in features that contain categories
 - Graphing Height vs. Weight scatterplot to prepare for Clustering  
## Completing the Cluster Analysis
- Analyze the best K-number of clusters to determine fit using Elbow method. Automatically chose 7 to see how accurate model can predict each category
- Build the K-means Cluster
## Comparing original Class Label and Clustering to measure Performance
- Export the result into a column and compare with the original class label
## Data Preparation for Supervised Learning
 - Convert categorical variables to numerical using dummy variables
## Model Building for Random Forest to predict Obesity Level
- Building the Random Forest Model
## Performance Measures for Random Forest
- Providing a classification report for various metrics
## Conclusion
- A detailed conclusion on why some methods work and some did not. Determine how well the models perform. Identify drawbacks, assumptions, and data that could possibly better the model in the future
