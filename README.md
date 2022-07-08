# rocks_nvidia_project

# Project Name

rocks_nvidia_project

Add short description of project here > 

This project uses image classification with dectect net to see, when the user holds up a rock to the camera, which type of rock it is (out of the three). 
Either igneous, sedimentary, and metamorphic. 

![add image descrition here](direct image link here)

https://www.pinterest.com/pin/124412008444930639/

## The Algorithm

Add an explanation of the algorithm and how it works. Make sure to include details about how the code works, what it depends on, and any other relevant info. Add images or other descriptions for your project here. 

The algorithm works by:

1. Getting the image from the user.
2. Seeing and determining, from the trained model, which type of rock it is.
3. Printing out which type of rock it is and the percentange of confidence that it knows that.

## Running this project

1. Add steps for running this project.

1. Getting an image.
2. Having a trained model with the images I gathered.
3. Get the results. 

2. Make sure to include any required libraries that need to be installed for your project to run.

from keras.models import load_model
from PIL import Image, ImageOps
import tensorflow
import numpy as np
import argparse

[View a video explanation here](video link in submission survey to nvidia. 
