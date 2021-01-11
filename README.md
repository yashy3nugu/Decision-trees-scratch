# Decision-trees-scratch

Python implementation of CART algorithm from scratch

# Dataset used

The dataset used is the bank note authentication data which can be found [here](https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data)

The dataset contains two classes (0 or 1) specifying whether a bank note is real or fake based on the following features.  

1.  variance of Wavelet Transformed image
2.  skewness of Wavelet Transformed image
3.  curtosis of Wavelet Transformed image
4.  entropy of image


# Procedure
The algorithm uses 'gini' impurity to split the data in successive nodes

# Results
The algorithm gives a testing accuracy of about 97%
