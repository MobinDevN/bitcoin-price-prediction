# Bitcoin Price Prediction with Machine Learning

This project predicts whether the **Bitcoin price** will go up or down
the next day using **Machine Learning models**.\
The models are trained on historical Bitcoin price data (`bitcoin.csv`).

------------------------------------------------------------------------

## Features

-   Data preprocessing and feature engineering
-   Data visualization (Matplotlib & Seaborn)
-   Multiple ML models:
    -   Logistic Regression
    -   Decision Tree
    -   K-Nearest Neighbors
-   Evaluation metrics: Accuracy & ROC AUC

------------------------------------------------------------------------

## Example Results

  ------------------------------------------------------------------------
  Model                   Prediction (Next Day)   Accuracy (%)   ROC AUC
  ----------------------- ----------------------- -------------- ---------
  Logistic Regression     0                       52.02          0.5419

  Decision Tree           1                       50.79          0.5062

  K-Nearest Neighbors     0                       54.31          0.5576
  ------------------------------------------------------------------------

------------------------------------------------------------------------

## Installation

``` bash
git clone https://github.com/MobinDevN/bitcoin-price-prediction.git
cd bitcoin-price-prediction
pip install -r requirements.txt
```

## Usage

``` bash
python bitcoin.ipynb
```

------------------------------------------------------------------------

## Dataset

The dataset used: `bitcoin.csv` (daily OHLCV values of Bitcoin).

------------------------------------------------------------------------

## Requirements

-   Python 3.10.11
-   pandas==1.5.3
-   numpy==1.23.5
-   matplotlib==3.7.1
-   seaborn==0.12.2
-   scikit-learn==1.2.2
