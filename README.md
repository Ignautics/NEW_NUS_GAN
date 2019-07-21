# vector-to-image using condition-gan【NUS_GAN】
## Overview
This is a tensorflow implementation of generating face images using condition-GAN named NUS_GAN. We've gotten great progress on the basis of [DCGAN](https://github.com/carpedm20/DCGAN-tensorflow) after using our algorithm. At present, this is just a preliminary version and coupled with our lack of ability, maybe there are still some problems in the codes. Please fell free to correct us.

The following is the model architecture. 


## Requirements
- python3.6+
- tensorflow
- numpy 
- scipy
- matplotlib
- others

## Datasets
- The model is currently trained on the [celeb-dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). Download the images and save them in ```data/ + "your dataset name" + /```.  Also put the ```label.txt``` in ```data/label.txt```. 

- Make empty directories in data, data/samples, checkpoint. They will be used for sampling the generated images and saving the trained models.

- You can also add your own dataset and transfer them to train the model, which is easy to modify.


## Usage


## Sample Images Generated


## Implementation Details


## Pre-trained Models



## References

