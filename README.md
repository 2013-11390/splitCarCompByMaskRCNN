# CarComponents Segmentation Example
This is an example of Mask RCNN for detecting tyre, light, number plate and grill of the car
using Python3, Keras, and Tensorflow.

## Installation
1. Download `mask_rcnn_coco.h5` from the From the [Releases page](https://github.com/matterport/Mask_RCNN/releases) page. 
2. Save installed h5 file in the root directory of the repo.

## Training
1. Download car images and masking json data in to the 'samples/carComponents/train/' and 'samples/carComponents/val/' for training.
2. In the /samples/carComponents, type following commands
'python main.py train --dataset=../carComponents --weights=coco'
3. You can see h5 file in the logs folder

## Segmentation
1. After getting .h5 file from training, put that h5 file into 'samples/carComponents'.
2. You have to change the route of h5 in 'Test_*_Trained_model.ipynb' for proper route.
3. You can test in the 'Test_*_Trained_model.ipynb' file for testing in Jupyter notebooks.


##Original Picture
Original Picture before Segmentation.
![](assets/original/4.jpg)

##After Tyre Segmentation
Visualize tyre of the picture after segmentation
![](assets/tyre/4.jpg)

##After Light Segmentation
Visualize light of the picture after segmentation
![](assets/light/4.jpg)

##After Number Plate Segmentation
Visualize number plate of the picture after segmentation
![](assets/number/4.jpg)

##After Grill Segmentation
Visualize grill of the picture after segmentation
![](assets/grill/4.jpg)

##After All Segmentation
Divide tyre, light, grill, number plate of the car
![](assets/total/4.jpg)