# Bitcoin Price Prediction with LSTM and Facebook Prophet - A CS 4675 Project

Author: [Shiyi Wang](mailto:swang793@gatech.edu)

## Introduction

This is a Bitcoin Price Prediction Model utilizing Keras Long Short-Term Memory (LSTM) and Facebook Prophet. The training dataset is the [Bitcoin Historical Data](https://www.kaggle.com/mczielinski/bitcoin-historical-data) from Kaggle.

## Getting Started

### Setup

#### Manual Setup

In order to run the Jupytor Notebook, you need to install the following python libraries and dependencies.

* [jupyter notebook](https://jupyter.org/install)
* [numpy (require version 1.19.5)](https://numpy.org/install/)
* [pandas](https://pandas.pydata.org/getting_started.html)
* [matplotlib](https://matplotlib.org/)
* [mplfinance](https://github.com/matplotlib/mplfinance)
* [sklearn.preprocessing](https://scikit-learn.org/stable/modules/preprocessing.html)
* [keras](https://keras.io/)
* [fbprophet](https://facebook.github.io/prophet/)

#### Setup with YAML File (Recommended)

1. Create the conda environment from `bit-env.yml` in the index directory.

```sh
conda env create -f bit-env.yml
```
> You may need to change the prefix in bit-env.yml

2. Activate the new environment. 
```sh
conda activate bit-env
```

### TA Grading Usage

Please run the following command in the index directory.

```sh
jupyter notebook bitPrediction.ipynb 
```

> Note: Before execution, I recommend search for `epochs = 200` and change the value from `200` to `20` to reduce the running time to 5 minutes.


Inside Jupyter Notebook, click on `Run All` to execute.
### Runnng Time Notes

The running time varies amomg diffrent machines. On Macbook Pro (2019):
* Total running time: ~ 40 minutes
  * Dataset Preparation and Visualization: ~ 2 minutes
  * LSTM Model with 200 Epochs: ~ 35 minutes
  * Facebook Prophet: ~ 2 minutes 

Running time with 20 Epochs on Macbook Pro (2019):
* Total running time: ~ 7 minutes
  * Dataset Preparation and Visualization: ~ 1 minutes
  * LSTM Model with 200 Epochs: ~ 5 minutes
  * Facebook Prophet: ~ 1 minutes


## Deliverables

* A comprehensive project report can be found at **Report on Bitcoin Price Prediction with LSTM Model and Facebook Prophet - Shiyi Wang**.
* Visualizations can be found at **Visualizations** directory.
* The Jupyter Notebook execution record can be found at **bitPrediction.html**.
* The Jupyter Notebook code can be found at **bitPrediction.ipynb**.
* The dependecy file for conda environment is **bit-env.yml**.
