# Prediction
Student Academic Performance Prediction

To launch Shiny App as an R script under RStudio Desktop Version:
runGist("e5e99035eed1d36043aecf38f79a54f5")

Make Sure before you launch Shiny App that you have installed and loaded the following libraries:
library(shiny)
library(ggplot2)
library(dplyr)
library(corrplot) # Draw a correlogram
library(gower) # Pre For caret
library(caret) # Partitioning and Recursive Feature Elimination (RFE) 
library(lattice) #already loaded by caret
library(partykit) # Pre For C50
library(C50)
library(kernlab)
library(mlbench) #data sets
library(randomForest) #Package to implement Random Forest and to be used for feature elmination
library(caretEnsemble)
library(MASS)
library(klaR)
library(nnet)

library(rpart)
library(rpart.plot)
library(e1071)
library(caTools)
library(zoo) # Pre For party
library(party) 
