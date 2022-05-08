## Asteroids Classification

In this project, we will work with a Kaggle dataset that contains Asteroid data from the NASA API. The "NASA: Asteroids Classification" dataset provides
data on measurements and characteristics for 4,687 asteroids. Our goal to identify potential hazardous and non-hazardous asteroid bodies from the data 
given, applying methods such as ridge regression and other statistical machine learning methods. Secondly, through trying various methods, we hope to 
pinpoint the method that is optimized for our goal of predicting potential hazardous asteroids.

## Dataset Description

There are 40 variables which describe various features of an asteroid, including but not limited to 
- Physical measurements of the asteroid body and its motion, 
such as Absolute Magnitude, Maximum and Minimum Estimated Diameter, and
Relative Velocity. We are also clued into some of the geometrical features
of the asteroid through information from variables such as Semi Major
Axis and Ascending Node Longitude.
- Orbital patterns and paths. This is illustrated through variables such
as Eccentricity and Orbital Period. We can also learn more about the
asteroid’s orbit relative to Earth and the Sun by looking at variables such
as Miss Distance, Perihelion Distance, and Aphelion Distance.
- Binary indication of hazardous or non-hazardous state.

## Project Summary

- Data cleaning
- Remove Multicollinearity
- Visualization and Information Extraction
- Model implementation
   1. Logistic Regression
   2. Naïve Bayes
   3. Support Vector Machine
   4. Decision Tree
   5. Random Forest
   6. K-nearest Neighbors
   7. XGBoost
- Model selection
