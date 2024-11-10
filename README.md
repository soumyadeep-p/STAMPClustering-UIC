# CS590 - Deep Learning Course Project

## Group Members:
1. Soumyadeep
2. Tanish
3. Aditya
4. Mihit
5. Pranav

## Project Overview
This project focuses on Unsupervised Image Clustering. We introduce a novel architecture that utilizes Vision-Language Models (VLMs) to generate pseudo-classes, aiming to enhance clustering and classification performance in an unsupervised setting.

## Repository Structure
The repository is organized into three folders, each corresponding to a dataset:
- **CIFAR-10**
- **MNIST**
- **STL-10**

Each folder contains the following files:
1. `Dataset_Processor.ipynb`: A notebook for dataset processing.
2. `KMeans_Clustering.ipynb`: A notebook for KMeans clustering.
3. `DBSCAN_Clustering.ipynb`: A notebook for DBSCAN clustering.
4. `STAMPClustering.ipynb`: A notebook for STAMP clustering.

## Download Pre-Processed Datasets
Please download the pre-processed datasets from the following links:

- [CIFAR-10](https://www.kaggle.com/datasets/soumyadeeppaul196/cifar-10-processed)
- [STL-10](https://www.kaggle.com/datasets/adityamandal1406/stl-10-processed)
- [MNIST](https://www.kaggle.com/datasets/adityamandal1406/mnist-processed)

### Results

| **Method**      | **Dataset** | **ACC** | **NMI** | **ARI** |
|-----------------|-------------|---------|---------|---------|
| KMeans          | CIFAR-10    | 61.0    | 53.0    | 41.0    |
| DBSCAN          | CIFAR-10    | 10.2    | 0.1     | 1.2     |
| SCAN            | CIFAR-10    | **88.3**| **79.7**| **77.2**|
| **Our Model**   | CIFAR-10    | 76.6    | 67.6    | 65.5    |
| KMeans          | STL-10      | 95.1    | 90.7    | 89.4    |
| DBSCAN          | STL-10      | 36.3    | 54.5    | 30.4    |
| SCAN            | STL-10      | 80.9    | 69.8    | 64.6    |
| **Our Model**   | STL-10      | **95.7**| **91.8**| **91.8**|
| KMeans          | MNIST       | 34.4    | **32.9**| **18.3**|
| DBSCAN          | MNIST       | 11.3    | 0.2     | 0.0     |
| **Our Model**   | MNIST       | **36.7**| 28.6    | 18.0    |

*Table 1: State of the Art Comparison*

