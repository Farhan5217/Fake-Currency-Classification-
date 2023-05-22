
# Fake Currency Classification Model



![Screenshot](https://tse4.mm.bing.net/th?id=OIP.3x-QNXbjyB7U9fn_hAfgiwHaDH&pid=Api&P=0&h=180)
## Introduction

This repository contains a machine learning model for fake currency classification. The model utilizes transformed wavelet characteristics, including variance, asymmetry, kurtosis, and image entropy, as input features to accurately classify banknotes as genuine or counterfeit.



## Dataset 

The dataset used for training and evaluation consists of samples of transformed wavelet characteristics extracted from banknotes. Each sample is labeled with the corresponding class, indicating whether it is a genuine or counterfeit banknote. The dataset does not include actual images of the banknotes but focuses solely on the transformed wavelet characteristics.

[https://github.com/Farhan5217/Fake-Currency-Classification-/blob/main/Currency_notes.txt]

## Model Architecture 

The machine learning model is based on logistic regression, a popular algorithm for binary classification tasks. It uses a linear combination of the input features followed by a sigmoid activation function to produce the classification output.

The model architecture is as follows:

Input Layer: 

The model takes four input features representing the transformed wavelet characteristics: variance, asymmetry, kurtosis, and image entropy.

Output Layer: 

The final layer of the model applies logistic regression by calculating a weighted sum of the input features and passing it through a sigmoid activation function. The output value represents the probability of the input features belonging to a genuine or counterfeit banknote
## Results

The performance of the Fake Currency Classification model achieved an accuracy of 98% on the test dataset using Logistic Regression.


## Contributing

Contributions to this project are welcome! If you have any ideas for improvements or find any issues, please open an issue or submit a pull request. Let's collaborate and make this project even better!