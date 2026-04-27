
# NFT Predictability Analysis

Machine Learning project analyzing Decentraland NFT land prices using transaction data, market features, and predictive modeling techniques.

## Project Overview

This project explores whether NFT assets can be predicted using data science and machine learning. Using Decentraland virtual land transaction data, the study evaluates pricing behavior, key valuation drivers, and model performance across NFT market conditions.

## Business Problem

NFT markets are volatile, speculative, and relatively new. Buyers, sellers, and investors often lack pricing benchmarks. This project aims to build predictive models that estimate NFT prices and identify factors influencing valuation.

## Dataset

**Source:** Decentraland NFT Estates Dataset

Features used include:

- Parcel count  
- Coordinates / location  
- District adjacency  
- Historical sales activity  
- Market timing variables  
- Estate classification labels  

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- LightGBM  
- CatBoost  
- Jupyter Notebook  
- Matplotlib / Seaborn  

## Models Implemented

- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  
- LightGBM Regressor  
- CatBoost Regressor  
- Autoregression / Time Series Models  

## Key Findings

- Estate classification was the strongest predictor of NFT price.  
- Parcel count significantly impacted valuation.  
- Models performed better on lower-priced common transactions.  
- Extreme high-value NFT sales were harder to predict.  
- Market timing variables also influenced price movement.  

## Project Files

```text
Models_reeya.ipynb        Main notebook
models.ipynb             Additional experiments
Model_Prasad.ipynb       Model comparison notebook
decentraland_dataset.csv Dataset
Updated poster.pdf       Final presentation poster
