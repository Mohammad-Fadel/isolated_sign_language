# Google - Isolated Sign Language Recognition

This repository contains the dataset and resources for the Kaggle competition "Google - Isolated Sign Language Recognition" hosted by Google. The competition is focused on the recognition of isolated signs in American Sign Language (ASL) from landmark data.

Link to the competition: https://www.kaggle.com/competitions/asl-signs/overview

## Data Overview

- Files: 94,479
- Size: 56.43 GB
- Type: parquet, csv, json

## Files Description

### 1. train_landmark_files

// (The rest of the file description)

## Added Functionalities to the Challenge

1. I added a visualization tool to convert the parquet files into videos to identify the motion as shown here:

   ![Alt Text](https://github.com/Mohammad-Fadel/isolated_sign_language/blob/master/input_from_user1.gif)
   ![Alt Text](https://github.com/Mohammad-Fadel/isolated_sign_language/blob/master/parqet_file.gif)
   

2. I created a way for the user to input a video and transform it into a parquet file, which gets preprocessed and passed through the trained model to predict the sign.

   ![Alt Text](https://github.com/Mohammad-Fadel/isolated_sign_language/blob/master/after_sign_translated.gif)

## Usage

1. Download the dataset from the Kaggle competition [page](https://www.kaggle.com/competitions/asl-signs/overview).
2. Extract the dataset into the desired directory.
3. Use the provided data in your machine learning or deep learning models to train and evaluate sign language recognition performance.

