# COMP551 (Fall-2019)-Applied Machine Learning 
# Mini Project 3 (Modified_MNIST_Classifier)
### Contributors: Shantanil Bagchi, Nikhil Podila, Mehdi Amian

## Abstract
In this project, a novel approach is proposed for classiﬁcation of the Modiﬁed MNIST dataset. The task is to identify the numerically largest value among three handwritten digits within each image. The proposed algorithm is a modiﬁed version of the well known VGGNet. Since convolutional neural networks (CNN) automatically capture the relevant features, we observe that additional feature selection and preprocessing on dataset are unnecessary. We also observe that data augmentation, optimizer tuning and model ensembling contribute to our best performance. The proposed algorithm reached an accuracy of 99.3% on the test set and ranked the ﬁrst on Kaggle’s Modiﬁed MNIST competition.
## Repository Structure
The repository contains following files:

* 1 Jupyter notebook files - COMP551 (Fall 2019) Applied Machine Learning Mini Project 3 (Subreddit Classifier).ipynb
* 2 Dataset files - reddit_train.data and reddit_test.csv
* 1 ReadMe file - ReadMe.md
* 1 Project writeup - writeup.pdf
* 1 Libraries file - requirements.txt

## Code Usage - (Python 3.6.2, conda 4.3.23)
1. Install required python libraries from requirements.txt
(refer to https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1 for steps to install libraries using requirements.txt)
2. Download all Jupyter notebook and Dataset files into one directory.
3. Open Jupyter notebook into that directory.
4. Select the required notebook (.ipynb file) and select "Run All" inside the jupyter notebook file.
