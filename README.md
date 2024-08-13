# DIAL: Data Imputation with Advanced Learning Framework

This research was supported by the European Research Council (ERC) under grant no. 952215 (TAILOR Project).

## Project Overview

The DIAL project, a collaboration between NVision Systems and Technologies S.L and the National and Kapodistrian University of Athens, addresses the challenge of missing data in Internet of Things (IoT) systems. Our goal was to enhance the quality and reliability of IoT data streams by developing advanced imputation techniques. The project integrates statistical analysis, signal processing, and deep learning methods into a novel framework.

## Objectives

- Improve the accuracy of data imputation for IoT systems with high percentages of missing data.
- Develop a robust methodology that efficiently handles large gaps and high missingness.
- Enhance the reliability and transparency of IoT applications, supporting better decision-making and operational efficiency.

## Developed Services

1. **Missing Data and Seasonality Analysis**  
   This service provides a comprehensive analysis of missing data patterns and seasonal variations within IoT datasets. It identifies and quantifies data gaps, assesses the impact of seasonality on data quality, and prepares the data for effective imputation.

2. **Imputation Framework**  
   The framework utilizes a multi-layer approach to address missing data, incorporating three distinct algorithms based on initial data analysis:
   - **Random Forest Model:** Known for its robust prediction capabilities.
   - **Convolutional Neural Network (CNN) Model:** Effective in capturing spatial patterns and complex data structures.
   - **ES-CC-BiLSTM Model:** Combines Exponential Smoothing, cross-correlation analysis, and BiLSTM Neural Networks to provide a comprehensive solution for complex temporal dependencies and large missing data gaps.

## Datasets Used

The framework was tested using real-world IoT data, including:
- **Energy Consumption Data:** UNICON dataset ([Kaggle](https://www.kaggle.com/datasets/cdaclab/unicon)).
- **Water Consumption Data:** Zenodo dataset ([Zenodo](https://zenodo.org/records/556152#.Y8kxenbMK5d)).

## Impact

This research significantly enhances the reliability of IoT data, supporting more accurate analysis and decision-making. It contributes to the development of sophisticated IoT applications and aligns with broader technological and sustainable development goals.
