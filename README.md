# Species-Present-Absent


# Introduction
This dataset is taken as a reference from  Machine Learning Certification Course in R programming language. This is a small dataset inlvolving 9 variables related to presence of species at land with slope, roughness, Avgtemp, etc. The variables include:
  -pb: Presence background 1- Species present , 0- Absent
  -Altitude
  -Aspect1
  -land
  -precipitation
  -roughness
  -slope
  -tempAvg 
  -tempMin
 
 
 # Working
 I have applied Decision Tree and Random Forrest Algorithms to predict the outcome of the classification of species being present or absent. pb is the predictor variable. 
 1. Cleaned the data for the varibales consisting of missing or zero values. 
 2. Imported various libraries Numpy, Pandas,  Matlpotlib, Seaborn
 3. Read the data from csv file 
 4. Scaled and fitted the data for normalization
 5. Imported the preprocessing for testing and training the dataset
 6. Applied Decision Tree Algorithm to predict the outcome
 7. Mapped with confusion matrix for accuracy of the predicted outcome
 8. Predicted the outcome with Random Forrest Algorithm with greater accuracy than Decision Tree Algorithm.
