# FinanceFormer-Transformer-based-Model-for-Investment-Portfolio-Optimization


## Description

The project aims to identify high-quality stocks with high relative returns in a portfolio of 300 stocks. The approach taken is to construct leading indicators (features) that can serve as signals of future price changes and are used as a basis for future predictions. The dataset contains 300 features for each of the 300 investments and the problem to be predicted is the relative return size of different investment targets on each day (time_id). The evaluation metric is the Pearson correlation coefficient, where a higher value indicates a more accurate prediction of the relative return size of all investment targets in the entire investment portfolio.

The project consists of several parts:

1.  Importing necessary libraries
2.  Loading the data
3.  Exploratory Data Analysis (EDA)
4.  Creating subplots
5.  Data preparation and dataset definition for modeling
6.  Defining a Financeformer model and a training loop

Requirements:

-   Python 3.x
-   PyTorch 1.9 or later
-   Pandas
-   Numpy
-   Matplotlib
-   TQDM

## Usage

The code provided can be executed as a Python script. The data needs to be downloaded and stored in the Parquet format, and the file path should be specified in the code. The user can modify the model architecture and training configurations as desired.

## Credits 

Dataset created by https://www.kaggle.com/evilpsycho42
