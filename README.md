# Project 1: Classify Images of Colon Cancer

## Description 

Using a modified version of the "CRCHistoPhenotypes" dataset for this task. The data set consists of 27x27 RGB images of colon cells from 99 different patients there are two tasks:

* Classify images according to whether given cell image represents a cancerous cells or not (isCancerous).
* Classify images according to cell-type, such as: fibroblast, inflammatory, epithelial or others.

![fig1](https://user-images.githubusercontent.com/54668379/117237706-b1995000-ae55-11eb-935f-6772981e618a.JPG)

 **Figure 1**: (a) Example histopathelogy image of the colon with individual cells marked with "blue" rectangles of size 27x27. (b) Example of different cell types present in histopathelogy images of the colon.

The correct classification of the images is given by the "data_labels_mainData.csv" and "data_labels_extraData.csv". For the first 60 patients, the medical experts have provided labels isCancerous and cell-type. However for the remaining 39 patients, the medical experts have only provided labels for isCancerous.

## Data set

* Download the data set here: [Link](https://drive.google.com/file/d/1g0za8TjFm4FFqQMy2N3_gSvi49E8q7J4/view?usp=sharing)

## Reference

* The original data set was published publicly as part of the following paper:

 K. Sirinukunwattana, S. E. A. Raza, Y. Tsang, D. R. J. Snead, I. A. Cree and N. M. Rajpoot, "Locality Sensitive Deep Learning for Detection and Classification of Nuclei in Routine Colon Cancer Histology Images," in IEEE Transactions on Medical Imaging, vol. 35, no. 5, pp. 1196-1206, May 2016, doi: 10.1109/TMI.2016.2525803.


