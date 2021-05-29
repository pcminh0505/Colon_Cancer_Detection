# Project 1: Classify Images of Colon Cancer

## Description 
Assume you are a team of machine learning engineers working for a biomedical startup company. Your task is to develop a machine learning system that can classify histopathology images of colon cells. A basic description of histopathology images can be found here.

You will be using a modified version of the "CRCHistoPhenotypes" dataset for this task. The data set for you to use in this assignment has been specifically prepared for you, and is provided on Canvas. The data set consists of 27x27 RGB images of colon cells from 99 different patients and you are expected to use the data set to perform two tasks:

* Classify images according to whether given cell image represents a cancerous cells or not (isCancerous).
* Classify images according to cell-type, such as: fibroblast, inflammatory, epithelial or others.

![fig1](https://user-images.githubusercontent.com/54668379/117237706-b1995000-ae55-11eb-935f-6772981e618a.JPG)

 **Figure 1**: (a) Example histopathelogy image of the colon with individual cells marked with "blue" rectangles of size 27x27. (b) Example of different cell types present in histopathelogy images of the colon.

The correct classification of the images is given by the "data_labels_mainData.csv" and "data_labels_extraData.csv". For the first 60 patients, the medical experts have provided labels isCancerous and cell-type. However for the remaining 39 patients, the medical experts have only provided labels for isCancerous.

## Data set

* Download the data set here: [Link](https://drive.google.com/file/d/1g0za8TjFm4FFqQMy2N3_gSvi49E8q7J4/view?usp=sharing)
## Requirements

* You must investigate at least one supervised machine learning algorithms for each of the two categories (Tasks). That is, you must build at least one model capable of predicting isCancerous, and at least one model capable of classifying the cell-type. One model with post processing label is not considered adequate.
* You are not required to use separate type(s) of machine learning algorithms, however, a thorough instigations should consider different types of algorithms.
* You are required to fully train your own algorithms. You may not use pre-trained systems which are trained on other datasets (not given to you as part of this assignment).
* For higher grades (HD/DI) you must explore how the data in "data_labels_extraData.csv" can improve the cell-type classification model and use it accordingly.
Your final report must conduct an analysis and comparison between classifying the two categories.
## Independent Evaluation

* As you don’t have access to histopathelogy images outside the dataset, the independent evaluation of this project is different to the other projects. A fundamental feature of the scientific process is reproducing existing work, and comparing new results against exist work.
* The original data set was published publicly as part of the following paper (available via RMIT library):

 K. Sirinukunwattana, S. E. A. Raza, Y. Tsang, D. R. J. Snead, I. A. Cree and N. M. Rajpoot, "Locality Sensitive Deep Learning for Detection and Classification of Nuclei in Routine Colon Cancer Histology Images," in IEEE Transactions on Medical Imaging, vol. 35, no. 5, pp. 1196-1206, May 2016, doi: 10.1109/TMI.2016.2525803.

Since publication, a number of papers, and online resources, have been published that use this data set.

* Your independent evaluation is to research a number of these published works. Then you must compare and contrast your results to those other works.
