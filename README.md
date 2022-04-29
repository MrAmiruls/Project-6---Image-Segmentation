# Project-6---Image-Segmentation (Cell Neuclei detection using semantic segmentation with U-Net)

## About
This project is a detection for the cell nuclei that happened from biomedical images effectively. It is fundamental task in microscopy image analysis. U-Net is proposed to potentially work with low resources computing. 

## IDE and Framework
The project is built with Spyder as the main IDE. The main framework used in this project are Tensorflow, Numpy, Matplotlib, OpenCV and Scikit-Learn.

## Methodology
The dataset files contains a train folder for training data and test folder for testing data. The dataset is in format of images for input and image mask for the labels. The input images are preprocessed with feature scaling. The labels are preprocessed such that the values are in binary 0 and 1. The train data is split into train-validation sets with ratio of 80:20.

The model was trained with a batch size of 16 and 100 epochs. Early stopping also applied in the model training. The training stops at epoch , with a training accuracy of %, and validation accuracy of %. The model training graphs are shown in figures below.
