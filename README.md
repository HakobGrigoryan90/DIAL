# DIAL: Data Imputation with Advanced Learning Framework
___________________________________________________________________________________________________________
This research was supported by the European Research Council (ERC) under grant no. 952215 (TAILOR Project)
___________________________________________________________________________________________________________

## Project Overview:
This collaborative project between NVision Systems and Technologies S.L and National and Kapodistrian University of Athens focused on addressing the challenge of missing data in Internet of Things (IoT) systems by developing advanced imputation techniques. This project aims to enhance the quality and reliability of IoT data streams through a novel framework that integrates statistical analysis, signal processing, and deep learning methods.

## Objectives:
•	Improve the accuracy of data imputation for IoT systems with high percentages of missing data.
•	Develop a robust methodology that handles large missing gaps and high missingness efficiently.
•	Enhance the reliability and transparency of IoT applications, supporting better decision-making and operational efficiency.

## Developed Services:
1.	Missing data and seasonality analysis: This service provides in-depth analysis of missing data patterns and seasonal variations within IoT datasets. It identifies and quantifies gaps, assesses the impact of seasonality on data quality, and prepares the data for effective imputation.
2.	Imputation Framework: The framework utilizes a multi-layer approach to address missing data. It incorporates three distinct algorithms based on initial data analysis:
  •	Random Forest Model: Used for its robust prediction capabilities.
  •	Convolutional Neural Network (CNN) Model: Leverages its ability to capture spatial patterns and intricate data structures.
  •	ES-CC-BiLSTM Model: Integrates Exponential Smoothing, cross-correlation analysis, and BiLSTM Neural Networks to provide a comprehensive imputation solution that handles complex temporal dependencies and large missing data gaps.

## Datasets Used: 
The framework was tested on real-world IoT data, including energy consumption data from the UNICON dataset (available at https://www.kaggle.com/datasets/cdaclab/unicon) and water consumption data from Zenodo (https://zenodo.org/records/556152#.Y8kxenbMK5d).

## Impact: 
The research significantly enhances IoT data reliability, supporting more accurate analysis and decision-making. It contributes to the development of more sophisticated IoT applications and aligns with broader technological and sustainable development goals.

