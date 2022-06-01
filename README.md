# Final-Project_Movie-Database


The movie dataset I am using contains 5000 movies catalogued by The Movie Database (TMDb). For this project, I will use this dataset to determine whether any information (budget, rating, actors/actresses, genre, etc.) about a movie can predict the total revenue of a movie. 

I chose this topic because I have a love of movies and I would like to see if I can develop a model about something I care so much about.

Link to Dataset => https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

# Outline

- Part 1: Data Preprocessing
   - Read Dataset
   - Define target variables

![targetvariables](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/DefineTargetVariables.png)

   - Remove null, unwanted, infinite values

![null](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/RemoveNullValues.png)

   - Feature Engineering
        - Encode genre column

![encode](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/EncodingGenreColumn.png)

        - Create Year column

![year](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/CreateYearColumn.png)

   - Feature Selection
   - Feature Transformation

![transformation](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/FeatureTransformation.png)

- Part 2: Exploratory Data Analysis
   - Statistical Analysis

![stats](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/StatisticalAnalysis.png)

   - Correlation Analysis

![correlation](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/CorrelationAnalysis.png)

   - Regression Target Analysis

![Target](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/BudgetRevenueCorrelation.png)

   - High VoteCount, High Revenue Trend

![HVCHR](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/HighRevHighVoteCountbyYear.png)

   - Vote Average, Popularity Comparison

![VAPop](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/VoteAveragePopularityCorrelation.png)

   - Genre feature analysis

![genre](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/GenreAnalysis.png)

   - General trend analysis

![yoy](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/RevenueYearoverYear.png)

- Part 3: Predictive and Comparison Modeling
   - Split into test/train sets

![tt](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/Train:Test.png)

   - BestRandomForestClassifer

![brfc](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/BRFC.png)

   - EasyEnsembleClassifer

![eec](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/EEC.png)

   - Deep Learning Module

![dnn](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/DNN.png)

   - Linear/Random Forest Regression

![lin](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/LinearRegression.png)

   - Logistic/Random Forest Regression

![log](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/LogisticRegression.png)

   - Optimized Linear/Random Forest Regression

![linop](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/LinearRegressionOptimized.png)

   - Optimized Logistic/Random Forest Regression

![logop](https://github.com/coxjack/Final-Project_Movie-Database/blob/main/Supporting%20Images/LogisticRegressionOptimized.png)

