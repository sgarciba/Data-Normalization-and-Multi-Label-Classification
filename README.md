# Data Normalization and Multi-Label Classification
Solving two multi-label classification problems using different ML models approaches. The data in both datasets has not been normalized, so we will be testing four methods to rescale our traning and test set. The goal of this project is to find the right combination of scalers and model that returns the best test accuracy score. 

The first dataset is the Wine set, already available in scikit-learn. It contains 178 observations of different wines and 13 features giving information about the amount of alcohol, malic acid and their colour intensity. The are three target labels: class0, class1 and class2.

The second problem refers to the USPS dataset of handwritten digits, easily accessible from the web site of Hastie et al. (2009):

- Trevor Hastie, Robert Tibshirani, and Jerome Friedman. Web site for The
Elements of Statistical Learning: Data Mining, Inference, and Prediction,
Second Edition, https://web.stanford.edu/~hastie/ElemStatLearn/.

It has two files (train and test) with 7291 and 2007 samples of images (16x16 greyscale pixels) plus its corresponding label. The range of possible numbers is from 0 to 9.

We will be working on both datasets separately, but applying the same process on each one:

1. Import and summarize the main aspects of the data.
2. Split randomly the big dataset into training and testing. 
3. Implementation of SVM without data normalization.
4. SVM performance after normalization.
5. MLP performance after normalization.



