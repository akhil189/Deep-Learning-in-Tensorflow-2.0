# Image Classification using Transfer Learning
> This mini-project implements Transfer Learning using TF-Hub module. 
## Objectives:
1. Building a Classifier to classify flower photos in tensorflow's flower-photos dataset.
2. Classifier is build using Mobilenet v2 pre-trained model. This model is trained on ILSVRC2012 [ImageNet Dataset] which has 1.2 million images belong to 1000 classes.
## Pre-Trained Model:
- [Mobilenet v2](https://tfhub.dev/google/tf2-preview/mobilenet_v2/classification/2)
## Dataset
- [Flowers Data](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)
- 3670 images belonging to 5 classes.
## Architeture:
- Mobilenet v2 (except last layer) + Fully Connected layer with 5 output nodes. 
## Results:

Model | Optimizer | Learning_rate | steps | Batch_size | Loss | Accuracy 
----- | --- | --- | --- | ------- | --------- |--------|  
Model_1 | Adam| 0.001  | 115  |  32  | 0.3430 |  0.9062|
