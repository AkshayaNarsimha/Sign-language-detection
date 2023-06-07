AUTHORS:
Ludwig Wideskär (luai18@student.bth.se),
Akshaya Bathula (akba21@student.bth.se)


CONTENTS OF THIS FILE
---------------------

* Description
* Requirements
* Installation


DESCRIPTION
-----------
The aim of our work for this project is to select three machine learning classification algorithms
and compare their predictive and computational performance against a training and validation dataset,
and a test dataset, with the images of American sign language letters.
The three machine learning algorithms that will be compared are K-NN (K-Nearest Neighbors),
SVM (Support Vector Machine), and CNN (Convolutional Neural Network).
The following five criteria will be used to evaluate the performance comparison for categorical classification:
1.	Computational performance in terms of training time.
2.	Predictive performance based on accuracy.
3.	Predictive performance based on precision.
4.	Predictive performance based on recall.
5.	Predictive performance based on F1-score (F-measure).


REQUIREMENTS
------------
The following requirements is needed for the program to run:

* The train and test datasets from kaggle-sign-language-dataset
  (https://www.kaggle.com/datasets/datamunge/sign-language-mnist)
  must be present within the same folder
* Python intrepreter

The following Python modules/libraries needs to be installed on the system:
* numpy
* matplotlib
* pandas
* seaborn
* sklearn
* datetime / time
* tabulate
* scipy
* scikit-posthocs (may need pip to install)


INSTALLATION
------------
Upload the files to Google Colab or use a similar online jupyter service.
Make sure that all the requirements are fulfilled.
You are now ready to run the program.
