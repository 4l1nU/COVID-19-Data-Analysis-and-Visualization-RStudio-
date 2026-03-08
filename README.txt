# COVID-19 Data Analysis and Visualization

## Project Overview
This project analyzes global COVID-19 datasets to identify factors that influence mortality rates across countries. The analysis focuses on relationships between total cases, total deaths, population size, and death percentages.

The project applies data visualization and machine learning techniques to explore patterns and classify countries based on mortality outcomes.

## Dataset
The dataset contains country-level COVID-19 statistics including:

- Total cases
- Total deaths
- Population
- Cases per million population
- Deaths per million population
- Death percentage

These variables were used to explore correlations and build predictive models.

## Tools and Technologies
The analysis was performed using **R** and several data science libraries:

- tidyverse
- ggplot2
- dplyr
- caret
- naivebayes
- rpart
- corrplot
- plotly

The project includes:

- Data preprocessing and transformation
- Exploratory data analysis
- Data visualization
- Machine learning models

## Data Analysis
The analysis includes several visualization techniques:

- Scatter plots for relationships between cases, deaths, and population
- Bar charts showing countries with the highest case and death counts
- Correlation matrices for different mortality classes
- 3D scatter plots to visualize relationships between multiple variables
- Boxplots comparing countries with different mortality rates

These visualizations help identify patterns and relationships in the dataset.

## Machine Learning Models
Two machine learning approaches were used to classify countries based on death percentage:

### Naive Bayes Classifier
- Dataset split into training (60%) and testing (40%)
- Cross-validation used for model evaluation
- Hyperparameter tuning applied
- Model performance evaluated using confusion matrix and ROC curve

### Logistic Regression
- Logistic regression used to predict mortality class
- Model evaluated using classification accuracy
- Important variables analyzed through model summary

## Results
The models were able to classify countries based on mortality indicators with reasonable accuracy.  
The analysis highlights relationships between:

- number of cases
- total deaths
- population size
- mortality rate

## Skills Demonstrated
This project demonstrates skills in:

- Data cleaning and preprocessing
- Exploratory data analysis
- Data visualization
- Machine learning
- Statistical modeling
- Working with real-world datasets in R

## Author
Alin Ungureanu