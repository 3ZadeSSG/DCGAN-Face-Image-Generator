<img src="https://img.shields.io/badge/java-%23ED8B00.svg?&style=for-the-badge&logo=java&logoColor=white"/>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/3ZadeSSG/Face-Generation-with-DCGAN/blob/main/LICENSE)

# Face Generation with Deep Convolutional Generative Adversarial Network
This repo implements Deep Convolutional Generative Adversarial Network (DCGAN) ([Paper Link](https://arxiv.org/abs/1511.06434)) to generate 32x32 RGB images of faces. The DCGAN architecture is implemented in PyTorch. The network can be modified to generate faces of higher resolution by training it with more higher resolution images.

### Dataset

For training CelebFaces Attributes Dataset (CelebA) has been used. The processed dataset contains 32x32 images to reduce compute time.
[Original Dataset Link](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
[Processed Dataset Link](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)

### Files
All code for training and network architecture can be found in `DCGAN_for_Image_Generation.ipynb`. For more detailed explanation of core concept `Original Training Notebook/dlnd_face_generation.ipynb` can be studied.

### Screenshots

| Sample 1  |  Sample 2 |
| ------------- | ------------- |
| <img src="https://github.com/3ZadeSSG/Face-Generation-with-DCGAN/blob/main/output/Input_Album.PNG"/> | <img src="https://github.com/3ZadeSSG/Face-Generation-with-DCGAN/blob/main/output/Output_Album.png"/> |


