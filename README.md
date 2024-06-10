# Genre Classification

![readme](https://github.com/kgregart/genre/blob/main/Images/readme.jpg)

## Objective

Classify the genre of music utilizing neural networking machine learning model demonstrating a predictive power of at least 75% classification accuracy.

## Instructions

Using SciKit and Spark, create a Python script that initializes, trains and evaluates a model that classifies the genre of music utilizing neural networking machine learning.

### Steps

__1. Data Collection__

- Retrieve data from https://www.kaggle.com/datasets/vicsuperman/prediction-of-music-genre.

__2. ETL:  Preprocessing__

- Use pandas to import the dataset and put into a DataFrame
- Use SciKit to normalize "key" and "mode" columns
- Transform categorical data to numerical in the "music_genre" column

__3. Split, Scale and Fit__

- Use sklearn to split the preprocessed data into a training and testing dataset
- Create a StandardScaler instances
- Fit the StandardScaler and scale the data

__4. Define Model__

- Identify the number of epochs, nodes, hidden layers and type of activation

  ![Neural_Network](https://github.com/kgregart/genre_classification/blob/main/Images/neural%20network.png)

__5. Train and Test the data__

- Fit the model to the training data
- Monitor the training process to adjust hyperparameters if needed
- Test the model on the unseen testing data to evaluate its performance
- Calculate accuarcy metrics
  
__6. Predict__

- Get the predicted class indices
- Convert the indices to genre labels


## Results Summary

![Accuracy](https://github.com/kgregart/genre_classification/blob/main/Images/A.png)



