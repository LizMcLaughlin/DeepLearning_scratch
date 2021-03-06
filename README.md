# Deep Learning Algorithms From Scratch

Implementing deep learning algorithms without use of python's ML libraries. Constrained to use of numpy, matplotlib, opencv. 


## Files

- ADAM_LogisticRegression.ipynb - implements/visualizes the ADAM learning rate and logistic regression on the [MNIST dataset](https://www.kaggle.com/oddrationale/mnist-in-csv)
- Multi-ClassClassifier.ipynb - implements single layer MC classifier from scratch using sigmoid activation function and cross entropy activation on the 'MC_data' dataset 
- MC_data.zip - holds data for Multi-ClassClassifier.ipynb

## To Run

- ADAM_LogisticRegression.ipynb - Download files and [MNIST dataset](https://www.kaggle.com/oddrationale/mnist-in-csv) into jupyter notebooks, and run cells
- Multi-ClassClassifier.ipynb - Unzip MC_data directory. Open in juptyper notebook and run cells.

## Results

### ADAM (ADAM_LogisticRegression.ipynb)

ADAM learn rate visualized -> epoch vs cost function (J) 
 
![alt text](https://github.com/LizMcLaughlin/images/blob/main/adam.png)

### Logistic Regression (ADAM_LogisticRegression.ipynb)

True positives = 2115 out of 2115 test samples. 
Model classified 100% of test samples correctly! Woot woot!

![alt text](https://github.com/LizMcLaughlin/images/blob/main/lr.png)

### Multi-Class Classifier (Multi-ClassClassifier.ipynb)

Accuracy = 92%. 
See below visualization of epoch vs cost function (J)

![alt text](https://github.com/LizMcLaughlin/images/blob/main/MCC.png)



Language: python3
