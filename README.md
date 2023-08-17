# WESAD Dataset Preprocessing

This repository contains code for preprocessing the WESAD (Wearable Stress and Affect Detection) dataset. The dataset consists of physiological and motion sensor data collected from wearable devices.


## Instructions

1. Set the `data_set` variable in the `WESAD.ipynb` script to the correct path to the dataset.
2. Run the `WESAD.ipynb` script to preprocess the data for each subject ID.
5. The preprocessed data will be stored as a list of DataFrames.

## Note

Couldn't append all the subject id's due to limited resource access - Trial version of Azure. 

## About the Dataset

The WESAD dataset contains physiological and motion sensor data collected from wearable devices. The preprocessing script extracts relevant signals, filters outliers using interquartile range, and normalizes the data.

