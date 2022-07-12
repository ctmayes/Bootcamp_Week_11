# Bootcamp_Week_11

# Prototype Crypto Portfolio Proposal for the Company Board of Directors

This program is designed to cluster cryptocurrencies by their performance in different time periods. Then it plots the results so that you can visually show the performance and recommend picks for investment.

Additionaly, this program makes use of the crypto_market_data.csv for data pull-in, which can be substitued to meet user need.

## Technologies

Within this program, we will make use of the following external python modules:

  -- pandas
  -- hvplot
  -- Path from pathlib
  -- KMeans from sklearn.cluster
  -- PCA from sklearn.decomposition
  -- StandardScalar from sklearn.preprocessing

  
  Additionally, this program was created within a python v3.7 build, and its relevant dependencies.

---

## Installation Guide

To utilize this program, within your terminal you will have to install the required libraries. Within your terminal, input the following commands:

```python
pip install -U scikit-learn
```

```python
conda install -c pyviz hvplot
```

After installing, run the following to ensure that sklearn and hvplot are installed:
```python
conda list scikit-learn

conda list hvplot
```

At the beginning of the *crypto_investments.ipynb* file, the technologies are calling in with this code:

```
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```

---

## Usage

To operate this program, open up your terminal of choice and navigate to the directory in which you have downloaded the files within this repository. Open Jupyter Lab with the command: 

```python
jupyter lab
```  

This should open jupyter lab to the filepath in which you have the repo file, and you simply need double click the *crypto_investments.ipynb* file to open it. Upon opening, select the menu button with two right facing arrows at the top of the notebook, which will run the entire file. It will ask you to confirm you wish to restart the file, to which you will confirm. Wait a few moments for the program to operate as intended, and peruse the resulting data at your leisure. If you wish, simply skip to the end for my analysis of the preceding information. 

---

## Contributors

Colton Mayes ctmayes@gmail.com

---

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.
