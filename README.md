# Project-6---Image-Segmentation (Cell Neuclei detection using semantic segmentation with U-Net)

## About
This project is a detection for the cell nuclei that happened from biomedical images effectively. It is fundamental task in microscopy image analysis. U-Net is proposed to potentially work with low resources computing. 

## IDE and Framework
The project is built with Spyder as the main IDE. The main framework used in this project are Tensorflow, Numpy, Matplotlib, OpenCV and Scikit-Learn.

## Methodology
The dataset files contains a train folder for training data and test folder for testing data. The dataset is in format of images for input and image mask for the labels. The input images are preprocessed with feature scaling. The labels are preprocessed such that the values are in binary 0 and 1. The train data is split into train-validation sets with ratio of 80:20.

The model was trained with a batch size of 16 and 100 epochs. Early stopping also applied in the model training. The training stops at epoch , with a training accuracy of %, and validation accuracy of %. The model training graphs are shown in figures below.
![accuracy](https://user-images.githubusercontent.com/85603599/166076957-8d77ca77-1988-41c2-8a8c-221b670b8e82.jpg)
![loss](https://user-images.githubusercontent.com/85603599/166077010-29ffd2b8-ca8e-4ec4-a737-f3ddad8b86f7.jpg)

## Result
![result](https://user-images.githubusercontent.com/85603599/166077036-8d99a635-8fc1-4db5-a0f5-c8a001f51328.jpg)
![results](https://user-images.githubusercontent.com/85603599/166077068-1cc4e49f-e329-4c78-88c4-c1fdbe0ae552.jpg)
![resultss](https://user-images.githubusercontent.com/85603599/166077085-88ca4a65-b66d-4c51-8849-0d40df230c3f.jpg)
