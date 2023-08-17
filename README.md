# WESAD Dataset Preprocessing

This repository contains code for preprocessing the WESAD (Wearable Stress and Affect Detection) dataset. The dataset consists of physiological and motion sensor data collected from wearable devices.


## Instructions

1. Set the `data_set` variable in the `WESAD.ipynb` file to the correct path to the dataset.
2. Run the `WESAD.ipynb` script to preprocess the data for each subject ID.
5. The preprocessed data will be stored as a list of DataFrames.

## Details

1. Uploaded the data in Azure data lake as blob containers.
2. Created the Azure databricks to run the python code.
3. Created data preprocess funtion to load pickle file, extract singnals from the data, finding interquantile range to normalise the data for the features.
4. Next step to store the data in the storage for data scientist for feature creation.

## Note

Due to limited resource access - Trial version of Azure data bricks, facing issue while adding notebook in data pipline.

## About the Dataset

The WESAD dataset contains physiological and motion sensor data collected from wearable devices. The preprocessing script extracts relevant signals, filters outliers using interquartile range, and normalizes the data.

