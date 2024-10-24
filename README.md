# Fish_Classification

## Fish Segmentation and Classification Dataset

This repository contains a large-scale dataset for fish segmentation and classification. The dataset was collected as part of a university-industry collaboration project at İzmir University of Economics and was later published in the Innovations in Intelligent Systems and Applications Conference (ASYU) 2020.
You can reach dataset's Kaggle link : https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset

Many thanks to O. Ulucan, D. Karakaya, and M. Turkan for their work in gathering this dataset: A Large-Scale Dataset for Fish Segmentation and Classification (2020).

## Overview

This dataset provides images of 9 different seafood types captured in a controlled environment. It is primarily intended for tasks such as:

Image Segmentation

Feature Extraction

Classification of Fish Species

### The dataset includes the following seafood types:

Gilt head bream

Red sea bream

Sea bass

Red mullet

Horse mackerel

Black sea sprat

Striped red mullet

Trout

Shrimp


## Data Details

The images were collected using two different cameras:

Kodak Easyshare Z650 (Resolution: 2832 x 2128)

Samsung ST60 (Resolution: 1024 x 768)

After collection, the images were resized to 590 x 445 to maintain the aspect ratio, followed by data augmentation including flipping and rotating the images. Each class in the dataset contains 2000 images (1000 RGB images and 1000 corresponding ground truth segmentation labels).

## Folder Structure

The dataset is structured as follows:

![image](https://github.com/user-attachments/assets/6ea133d3-2fde-4244-9a54-537fa7be4c84)

    
## Example Usage

Each seafood type has its corresponding segmentation ground truth in the folder named *_GT. The RGB images can be used for training classification models, while the ground truth images are useful for segmentation tasks.

For instance, to access the ground truth labels for shrimp:

![image](https://github.com/user-attachments/assets/b5adc795-359a-4946-9e23-43d097bf1641)

## Purpose of the Dataset

The dataset was created to:

Evaluate and compare common segmentation, feature extraction, and classification algorithms such as:

Semantic Segmentation

Convolutional Neural Networks (CNNs)

Bag of Features

The experimental results have shown that the dataset is suitable for tasks like object segmentation, feature extraction, and classification.

