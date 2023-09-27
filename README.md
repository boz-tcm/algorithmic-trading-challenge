# Columbia Engineering FinTech Bootcamp 2023-06

> Project: Module 14 Algorithmic-Trading-Challenge

> Background: With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America.

> Purpose: In this activity, we use our newfound Python, time-series, and Prophet skills to to find out whether the ability to predict search traffic at MercadoLibre can translate into successfully trading the stock.  

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->

## General Information
- Our project was designed to use Scikit-learn libraries, including sklearn preprocessing, cluster, decomposition, and algorithms KMeans and PCA to analyze factors, or features, in the cryptocurrency market.
- We examined four variations of an algorithmic trading machine learning model:
    1. Baseline model, characterized by a notably very short training period, comprising just over 3% of the entire in-sample dataset, AND short-term moving average ('Fast') and long-term moving average ('Slow') technical trading price signals of 4 and 100 periods, respectively. `machine_learning_trading_bot_baseline.ipynb`
    2. A training-period variation to the baseline model, increasing the training period to a more traditional 76% of the in-sample dataset (75%-80% is customary), leaving 24% of the in-sample for testing, corresponding to increasing the model's offset parameter from 3 months to 46 months!  `machine_learning_trading_bot_training_period.ipynb`


## Technologies Used
- Python Version 3.10.12
- Prophet Version 1.1.4
- Jupyter Notebook within the VS Code IDE for both Jupyter Notebook 'crypto_investments.ipynb' and a README markdown file.

## Features

## Screenshots
##### `Sample project screenshot depicts comparison of KMeans clustering models for cryptocurrency scaled market data before and after feature reduction using Principal Component Analysis (PCA):`

![A screenshot depicts comparison of KMeans clustering models for cryptocurrency scaled market data before and after feature reduction using Principal Component Analysis (PCA).](Images/final_analysis_cluster_comparisons.png)

## Setup
- GitHub Repository
    - name: 'unsupervised-learning-challenge'
    - location: uploaded to Bootcamp homework submission online portal and available publicly at:
        - [GitHub Repository](git@github.com:boz-tcm/unsupervised-learning-challenge.git)
- Python Standard Library (Version 3.10.12)
- Python Libraries and Modules:
    - prophet 1.1.4
    - pathlib and Path function
    - hvplot.pandas
    - sklearn.preprocessing and StandardScaler object
    - sklearn.cluster and KMeans object
    - sklearn.decomposition and PCA object
- Jupyter Notebook(s):
    - name: 'crypto_investments.ipynb'
    - location: 'unsupervised-learning-challenge/'
- Data
    - location: 'unsupervised-learning-challenge/Resources/'
- Images
    - location: 'unsupervised-learning-challenge/Images'

## Usage
The script is run in the Jupyter Notebook 'crypto_investments.ipynb', within the 'unsupervised-learning-challenge' directory, executed using the Notebook environment's 'Run All Cells...' command.

## Project Status
Project is: _complete

## Room for Improvement
Room for improvement:   _

To do:  _

## Acknowledgements

## Contact
Created by Todd C. Meier, tmeier@bozcompany.com - feel free to contact me!

<!-- ## License --> All rights reserved.