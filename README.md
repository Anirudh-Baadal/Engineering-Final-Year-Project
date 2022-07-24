# Pneumonia Detection Using Deep Learning Algorithms

## Input:

![image](https://user-images.githubusercontent.com/93869586/180639168-bb03a0b2-1505-45b0-a546-d3748ec6d770.png)


## Output:

![image](https://user-images.githubusercontent.com/93869586/180639130-3293a260-e168-45f4-b24f-7a781979d368.png)


## Confusion Matrix and Accuracy 

![image](https://user-images.githubusercontent.com/93869586/180639540-bcd12665-2e24-453a-bca9-3531430961ad.png)


## Methodology:

In the project, labelled Chest X-Ray images are fed as input to the system. The
Chest X-Ray images are then pre-processed using various image processing techniques such as Normalization, Translation, Rotation etc. These pre-processed images are fed into the CNN model in the form of batches after shuffling them. This
will help in improving the performance of the CNN. Then in the next stage we
obtain segments of lungs by using image segmentation, which is a vital step in
pulmonary image analysis for identifying the regions of lungs infected. In image segmentation different features of the images will be extracted using a deep
CNN model consisting of convolutional layers, batch normalization, ReLU (Rectified Liner Unit) activation and max pooling layers. The final layer will be a fully
connected layer with output features corresponding to the number of classes which
will help in classifying the image i.e., predicting the disease label.

## Dataset:

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
