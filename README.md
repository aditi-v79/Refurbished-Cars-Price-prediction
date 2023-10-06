# Refurbished-Cars-Price-prediction

## Introduction

In today's automotive industry, new car prices are determined by manufacturers, often including additional costs in the form of government taxes. While this assures customers of the value of their investment in a new car, the rising prices and financial constraints have led to a global increase in used car sales. This shift necessitates the development of a used car price prediction system that can accurately determine the worthiness of a used car based on various features. Existing online services offer this functionality, but their prediction methods may not always yield the best results. This project aims to leverage different models and systems to enhance the accuracy of predicting the actual market value of used cars, facilitating informed buying and selling decisions.

## Existing System

The current system employs Linear Regression for used car price prediction. However, the performance of linear regression leaves room for improvement. Noticeable differences between actual and predicted values indicate the need for alternative models to achieve more accurate results.

## Proposed System

To address the limitations of the existing system, we have chosen to implement the XGBoost system for price prediction. XGBoost is a specific implementation of the Gradient Boosting method, known for its accurate approximations in finding the best tree model. It incorporates various techniques that contribute to its high success rate, particularly with structured data. XGBoost also boasts advantages such as rapid training and parallelization across clusters. Therefore, XGBoost is a valuable addition to this study, offering improved predictive capabilities.

## Limitations

While this study aims to predict used car prices using different models, it encountered a limitation in terms of dataset size. The dataset used for training and testing comprised only 6000 observations. More extensive datasets would enhance the robustness of predictions and yield stronger insights.

## Requirements

### Software Requirements

- Operating System: Windows 7, Windows 8 (or higher versions)
- Programming Language: Python 3.5 and libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.
- Web Browser: Mozilla Firefox (or any modern browser)

### Hardware Requirements

- Processor: Pentium 3, Pentium 4, or higher
- RAM: 2GB/4GB RAM or higher
- Hard Disk: 40GB or higher

## Getting Started

To use this system, make sure you have Python and the required libraries installed. You can run the code provided in the repository to predict used car prices based on your dataset.

## License

This project is open-source and available under the MIT License. Feel free to customize and use it for your own purposes.
