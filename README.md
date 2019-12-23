# Image-Captioning
This is a project in which I have to generate captions from a given Image dataset


![alt text](https://github.com/raunak222/Image-Captioning/blob/master/Image/encoder-decoder.png)

##  Motivation/Purpose: 
-  We learn how to load and pre-process data from the COCO dataset. We  also designed a CNN-RNN model for automatically generating image captions.

### Major Milestone would be:
#### 1 Explore the Data Loader
#### 2 Use the Data Loader to Obtain Batches.
#### 3 Experiment with the CNN Encoder.
#### 4 Implement the RNN Decoder
## - How to Use 
- Go through instruction [here](https://github.com/raunak222/Image-Captioning/blob/master/instructions.txt)

## - Some Visualization
 ### Input Image
 ![alt text](https://github.com/raunak222/Image-Captioning/blob/master/Image/download%20(5).png)
 ### Caption
 #### A jiraffe Standing in a field
### Input Image
![alt text](https://github.com/raunak222/Image-Captioning/blob/master/Image/download%20(4).png)
### Caption
#### A man takes a slice of pizza from its plate.
 ### Input Image
 ![alt text](https://github.com/raunak222/Image-Captioning/blob/master/Image/download%20(7).png)
 ### Caption
 ####  a surfer is riding a wave in the ocean
## Explaining Encoder and Decoder
  ## Encoder: 
  ![alt text](https://github.com/raunak222/Image-Captioning/blob/master/Image/encoder.png)
  For Encoder we use ResNet-50. ResNet-50 is a convolutional neural network that is trained on more than a million images from the ImageNet database. The network is 50 layers deep and can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 224-by-224.   

## Decode:

## Developer 
  Raunak Sarada  
  - [Github](https://github.com/raunak222) 
  - [linkedin](https://www.linkedin.com/in/raunak-sarada)
## Resources 
- http://cocodataset.org/#home
- https://blog.openmined.org
- https://arxiv.org/pdf/1405.0312.pdf

## Citation
- Udacity Computer Vision Nanodegree
