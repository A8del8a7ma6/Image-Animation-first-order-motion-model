<b>!!! Check out our new [paper](https://arxiv.org/pdf/2104.11280.pdf) and [framework](https://github.com/snap-research/articulated-animation) improved for articulated objects</b>

#Description of the project as all 

This project animates faces from videos and images. Here the model takes a driving video and maps its motion over static images to give a realistic appearance. The model loading uses Python, and the source code is available in the repository. 

This example shows a method of animating static source images through unsupervised region detection. The model uses a driving video and maps its motion over still images to give a realistic appearance.

First Order Motion Model (FOMM) consists of two main parts: motion estimation and image generation. Motion estimation contains coarse motion estimation, which is modeled as sparse motions between separate object parts, and dense motion, producing an optical flow along the confidence map for the entire image.


# First Order Motion Model for Image Animation

This repository contains the source code for the paper [First Order Motion Model for Image Animation](https://papers.nips.cc/paper/8935-first-order-motion-model-for-image-animation) by Aliaksandr Siarohin, [Stéphane Lathuilière](http://stelat.eu), [Sergey Tulyakov](http://stulyakov.com), [Elisa Ricci](http://elisaricci.eu/) and [Nicu Sebe](http://disi.unitn.it/~sebe/). 

## Example animations

The videos on the left show the driving videos. The first row on the right for each dataset shows the source videos. The bottom row contains the animated sequences with motion transferred from the driving video and object taken from the source image. We trained a separate network for each task.
