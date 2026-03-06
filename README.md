# Mental Health Predictor Overview

![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white) 
![dplyr](https://img.shields.io/badge/dplyr-1F77B4) 
![ggplot2](https://img.shields.io/badge/ggplot2-EA5E5E) 
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-4CAF50)

This project explores predicting mental health outcomes based on behavioral and demographic variables. It demonstrates **Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization, and Regression Modeling** in R using real-world survey data. The goal was to predict the number of "poor mental health days" reported in the past 30 days based on several variables such as exercise habits, income, and interview timing.

_This repository provides a high level overview of the project. The [complete project](https://github.com/samcirceo/MentalHealthPredictor), including code and detailed results, is available in a private repository. If you would like access, please contact me with your GitHub username._

<p align="center">
  <img src="https://raw.githubusercontent.com/samcirceo/samcirceo/main/images/mentalhealth.jpeg" width="350">
</p>


### Overview of Project
- **Data cleaning**:  Removed missing values, corrected datatypes, encoded variables, and created categories through binning.
- **Exploratory Data Analysis**: Visualized patterns and relationships among key variables 
- Modeling: Built a a **Linear Regression Model** to predict number of poor mental health days. 


### Key Takeaways
- The regression model explained only a small portion of variance (R<sup>2</sup> ~ 0.03). This highlights that this model is insufficient for accurate predictions. 
 - Mental Health is a complex phenomenon, and simple linear regression is not enough to capture the variability. 


### Future Improvements
- Incorporate additional variables such as stress levels, sleep quality, work environment, and other demographics to improve predictive power
- Experiment with more complex models like Support Vector Regression, Decision Trees, or Ensemble methods



