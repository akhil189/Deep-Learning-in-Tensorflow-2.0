# Multi-class Image Classification
> This project implements multi-class Image Classification using CNN to classify images belonging to  7 different classes.
## Objectives:
1. Pre-processing the dataset to split and randomly shuffle it into Train(75%), Val(15%) and Test(15%) such that each class in Train set has equal number of images.
2. Building a CNN Classifier to classify photos in small dataset containing images of 7 classes.
3. Improve accuracy by using augmentation and early stopping.
## Architeture:
   3 (Convolutional + Pooling) Layers + 2 Fully-Connected Layers 
## Results:

Model | Optimizer | Learning_rate | steps | Batch_size | Loss | Accuracy 
----- | --- | --- | --- | ------- | --------- |--------|  
Model_1 | Adam| 0.01  | 20  |  128  | 1.6214  | 0.3748 |

