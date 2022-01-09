# Implementing of a Multiple Artistic Style Transfer #

This is an revised implementation of the "[A Neural Algorithm of Artistic Style](http://arxiv.org/abs/1508.06576)". This uses the selected filtered responses of a pre-trained model (VGG-19) to capture low level to high level features and transfer them to the content image.

You can also just replace with your own images and to generate your new painting.

# Before running, set up style images and content image:

STYLE_IMAGE1 = 'images/Girl before a Mirror.jpg'

STYLE_IMAGE2 = 'images/Cafe Terrace at Night.jpg'

CONTENT_IMAGE = 'images/Ryoko Hirosue.jpg'

# How to run

You will need to install dependencies:

- TensorFlow
- Scipy
- Numpy

You will need to download the VGG-19 model from Model Zoo at [https://github.com/BVLC/caffe/wiki/Model-Zoo](https://github.com/BVLC/caffe/wiki/Model-Zoo).

Then just run Multiple Artistic Style Transfer.py.
