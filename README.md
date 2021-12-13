# small-boat-detector
This repository contains the trained yolo v3 model weights and configuration file to detect small boats in satellite imagery, used in the paper "Monitoring visitation at North Carolina artificial reefs using high-resolution satellite imagery" submitted for review in Ocean and Coastal Management.

- [Requirements](#Requirements)
- [Test on an image](#Test-on-an-image)
- [Tips for project set-up](#Project-Tips)


## Requirements
This project used the darknet neural networks for object detection from the [AlexeyAB/darknet](https://github.com/AlexeyAB/darknet) repository. To use the trained model weights and the configuration file that was used in this study to detect boats in Planet satellite imagery, you would need to install darknet according to the directions in the darknet.

Once successfully installed, run the test code provided in the darknet README file:
  `./darknet.exe detect cfg/yolov3.cfg yolov3.weights data/dog.jpg`

## Test on an image
Also included is an image from the study. 
path to image here
To use our trained weights to detect the boats in this image, run the following code:

## Project Tips
Darknet will be installed on your computer. We found that it was easiest to have all files and data associated with detection to be located within the darknet directory. Within the directory, you should have the following folders (these should already exist from downloading darknet):
- data
- obj
- 
