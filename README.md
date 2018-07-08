# LocalFeatureExtraction4CBIR

## About
For content based image retrieval, current popular approaches rely on deep learning.
However, the Bow-base approach is also useful in image retrieval related applications, such as place recognition.
As a PhD student, I have wasted much time on the feature extraction step and catched many bugs.
Therefore, I want to high-light the local feature extraction in the Githhub repository.
This introdcution is orginazed by the software or public code provided by different research groups in this field. 

### VGG
code: http://www.robots.ox.ac.uk/~vgg/research/affine/detectors.html#binaries

This software consists of two steps, the keypoints detectors and SIFT feature extraction. The first step provides more opitions for key-point detection, such as the low threshold of cornerness. The low threshold can extract more keypoints which is usefull for place recognition application. 

### VLFeat Toolbox

code: http://www.vlfeat.org/

The VLFeat is an open-source toolbox for computer vision. The VLfeat toolbox is used in Torri's CVPR paper.

### INRIA
code: http://lear.inrialpes.fr/~jegou/data.php

This code is released with the famous public dataset Holidays and Flickr1M [1]. 

### CMP
code: http://cmp.felk.cvut.cz/~perdom1/code/index.html (Github homepage: https://github.com/perdoch/hesaff)

This code is provided with the CVPR2009 paper, which is latter popularly used in extracting local features in landmark images, such as the Oxford and Paris dataset. This software is suit for upright buildings to extract local features

## Application

### Image Retrieval


### Place Recognition


