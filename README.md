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
## 3. Completing the Cluster Analysis K = 7
- Analyze the best K-number of clusters to determine fit using Elbow method. Automatically chose 7 to see how accurate model can predict each category
- Build the K-means Clustering Algorithm
## 4. Comparing original Class Label and Clustering to measure Performance K = 7
- Export the result into a column and compare with the original class label
## 5. Completing the Cluster Analysis K = 4
- Build the K-means Clustering Algorithm
## 6. Comparing original Class Label and Clustering to measure Performance K = 4
- Export the result into a column and compare with the original class label
## 7. Data Preparation for Supervised Learning
 - Convert categorical variables to numerical using dummy variables
## 8. Model Building for Random Forest to predict Obesity Level
- Building the Random Forest Model
## 9. Performance Measures for Random Forest Models
- Providing a classification report for various metrics
## 10. Check optimal number of n_estimators
- By doing this we can reduce the training time and to remove unnecessary trees.
## 11. Tuned Random Forest Model and Performance Measures
- Building the Random Forest Model with appropriate n_estimators
- Providing a classification report for various metrics
