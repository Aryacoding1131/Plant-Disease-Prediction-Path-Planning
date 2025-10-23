# Plant-Disease-Prediction-Path-Planning-for-UAV
This repo mainly contains plant disease prediction and Path Planning for UAVs

As a part of acadimics I and my team developed the Precision Agriculture: Plant disease prediction and Path planning for UAVs
**Very special thanks to my teammates who took part in developing the project**


Mainly we used CNN Model and also Dataset used here is PlantVillage Dataset (Link: https://www.kaggle.com/datasets/emmarex/plantdisease)
We converted the images of the dataset to NDVI (Normalized Difference Vegetative Index) 

#Formula for NDVI : NDVI = (NIR - RED)/(NIR + RED)

The NDVI images looks somthing related to grayscale images then we trained the model, to get the novality we used Grad-cam that mainly 
extracts the important features from the images and creates the heatmaps

then we trained and saved the model using pickle

Coming to path planning we used A* and RRT algorithm 

A* purely works on heuristics and RRT creates the Random Tree
A* gives more optimal path and where RRT somtimes creates the issues like no path found. And it uses backtracking to solve the issues


