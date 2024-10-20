# LULC
# Land Cover and Land Use Change Detection in Washington D.C.

This repository contains the code and data for the project "Land Cover and Land Use Change Detection in Washington D.C. Using Sentinel-2 Data and Machine Learning Approaches."
You can find the paper for this project <a href="https://github.com/moeinp70/LULC/blob/main/EarthObservationAdvanced.pdf" target="_blank"> here</a>.</br>
## Project Overview

This study investigates land cover and land use (LCLU) changes in Washington D.C. between 2017 and 2024 using Sentinel-2 satellite imagery. By employing three machine learning approaches—Random Forest (RF), Multi-Layer Perceptron (MLP), and Convolutional Neural Network (CNN)—we aim to classify and analyze these changes. Preprocessing steps included cloud masking, mosaicking, and histogram matching to normalize images. Our findings highlight significant transitions from forested areas to urban developments, emphasizing the impact of urban expansion on green spaces. The results underscore the effectiveness of combining remote sensing data with advanced machine learning techniques for environmental monitoring. The complete codes used in this study are available on our GitHub page.




## Table of Contents
- [Introduction](#introduction)
- [Data Acquisition](#data-acquisition)
- [Preprocessing](#preprocessing)
- [Classification Approaches](#classification-approaches)
- [Results](#results)
- [Conclusion](#conclusion)
- [Requirements](#requirements)
- [References](#references)

## Introduction

This project aims to monitor and analyze changes in land cover and land use in Washington D.C. over a period from 2017 to 2024. The analysis focuses on identifying significant transitions, such as deforestation and urban expansion, and emphasizes the impact of these changes on green spaces.

## Data Acquisition

Sentinel-2 L2A level images from 2017 and 2024 were acquired using the Google Earth Engine (GEE). The region of interest (ROI) was defined using a shapefile containing the boundaries of Washington D.C. We used 10 bands from Sentinel-2, excluding bands 1, 9, and 10.

## Preprocessing

Preprocessing steps included:
- Cloud masking (automaticaly applied)
- Mosaicking (automaticaly applied)
- Histogram matching using Scikit-image to normalize the images

## Classification Approaches

Three machine learning classifiers were used:
- **Random Forest (RF)**: An ensemble learning method implemented using Scikit-learn.
- **Multi-Layer Perceptron (MLP)**: A neural network model implemented using Scikit-learn's MLPClassifier.
- **Convolutional Neural Network (CNN)**: A deep learning model implemented using TensorFlow.

## Results

Accuracy metrics for each classifier were computed and compared. The results highlight significant transitions, particularly from forest to urban areas, and underscore the impact of urban expansion on green spaces.

## Conclusion

This study successfully applied RF, MLP, and CNN classifiers to detect LCLU changes in Washington D.C. from 2017 to 2024. The CNN model, in particular, demonstrated the ability to capture spatial patterns effectively. The study underscores the importance of combining remote sensing data with advanced machine learning techniques for environmental monitoring.

## Requirements


- Python 3.6+
- TensorFlow
- Scikit-learn
- Rasterio
- Geopandas
- Matplotlib



Feel free to adjust the details and sections as necessary for your project.
