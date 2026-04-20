# Identification-of-Geometric-Shapes-and-Estimating-its-size-through-CNN-

# Geometric Shape Detection with CNN

Deep learning model for automated industrial packaging inspection.

**Results:** 97% classification accuracy on 16,000 images  
**Tech:** Python, TensorFlow, OpenCV, data augmentation  
**Context:** Final Year Project, UET Peshawar (supervised by Dr. Atif Jan)

## What it does
Identifies geometric shapes and estimates their size using a custom 
CNN trained from scratch — designed for automated quality control 
in industrial packaging lines.

## How to run
pip install -r requirements.txt  
python train.py  
python predict.py --image sample.jpg

# Data
Source: (https://www.kaggle.com/datasets/smeschke/four-shapes)
Shapes: Triangle, Circle, Square, Star
Image Size: 200x200 pixels, grayscale

