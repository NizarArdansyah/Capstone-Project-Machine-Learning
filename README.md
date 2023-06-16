# Capstone-Project-Machine-Learning
![image](https://github.com/NizarArdansyah/Capstone-Project-Machine-Learning/assets/82304620/57748f38-450a-4039-a6d9-05087643f35c)

This repository was created to accommodate the Capstone (Taniland) project model in the Wake 2023 Machine Learning Path program, which is a land management application aimed at the agricultural industry so that it can assist in better land management through the features we have made in this application.


To make a plant recommendation feature we create a model through temperature, humidity and image data according to land conditions, in making this feature we use 3 algorithms to build a planting recommendation model:
* by IoT
   * Clustering : Kmeans
   * Classification : Decission Tree
* by Image
   * Deep Learning : CNN

Steps to run this project:
1. Crop Recomendations
* Clustering :
   * Upload crop_recomendation.csv into notebook
   * Run runtimes
   * The results of each cluster will become a new dataset
   * Export the new dataset to a .csv file for classification using a decision tree
   * The model will be saved in .pickle format 
* Klasifikasi :
   * Train each new cluster dataset into a decision tree model
   * The model will be saved in .pickle format

2. Soil type prediction
* Enter data into Google Drive
* Customize the data train path
* Run runtimes 
* The model will be saved in .h5 and .json format


 
