# Final-Project_Movie-Database


The movie dataset I am using contains 5000 movies catalogued by The Movie Database (TMDb). For this project, I will use this dataset to determine whether any information (budget, rating, actors/actresses, genre, etc.) about a movie can predict the total revenue of a movie. 

I will also attempt to predict whether a movie's revenue will exceed its budget

I chose this topic because I have a love of movies and I would like to see if I can develop a model about something I care so much about.

# Outline

- Part 1: Data Preprocessing
   - Read Dataset
   - Define target variables

![targetvariables]()

   - Remove null, unwanted, infinite values
   - Feature Engineering
        - Encode genre column
        - Create Year column
   - Feature Selection
   - Feature Transformation
- Part 2: Exploratory Data Analysis
   - Statistical Analysis
   - Correlation Analysis
   - Regression Target Analysis
   - Year over Year Trend
   - Trend Analysis of vote_average
   - Genre feature analysis
   - General trend analysis
- Part 3: Predictive and Comparison Modeling
   - Split into test/train sets
   - BestRandomForestClassifer
   - EasyEnsembleClassifer
   - Deep Learning Module
   - Linear/Random Forest Regression
   - Logistic/Random Forest Regression
   - Optimized Linear/Random Forest Regression
   - Optimized Logistic/Random Forest Regression
