
---

# Time Series Forecasting for Air Quality Prediction (PM2.5) - README.md
- Name: `Ngoc Duy Tran`

## README 

**Research Goal:** Time series forecasting is a technique to predict a response variable over a period of time based on historical data. It plays a vital role in many domains, ranging from financial and quantitative trading to air quality prediction of pollutants - PM2.5.

This paper focuses on a multivariate time series forecasting algorithm for air quality performed on **Beijing Air Quality Dataset** by using machine learning and deep learning models. More importantly, this paper also implements multivariate **N-BEATS** architecture - a state-of-the-art model, which is a pure neural network that beats Sequence to Sequence(seq2seq) models such as ES-RNN in its original paper.

**Keywords:** multivariate time series forecasting, N-BEATS, deep learning models

**Timeline:** The timeline for the research area is 2017 - 2021.

## PIPELINE

To run the pipeline, please follows all the steps and run the files in sequential order:

The dataset has already been downloaded and preprocessed and uploaded to curated directory. Therefore, there is no need to run files in script directory to download and preprocess the data

To run the modelling section, please visit the `notebooks` directory and run the files in order:
1. `modelling.ipynb`: This notebook details all necessary preprocessing steps to transform the data into smoother and more easily interpretable data to apply the machine learning/ deep learning methodologies on such as Fourier Transform, spline imputation. This notebook covers N-BEATS extension for multivariate data and other Seq2Seq models such as GRU and LSTM.

To understand about the methodology, please refer to the repo directory and read the report pdf file.

## CONTACT
Should you have any questions, please contact me via the email: ngocduyt@student.unimelb.edu.au

---