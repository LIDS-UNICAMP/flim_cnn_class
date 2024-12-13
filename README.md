# FLIM CNN Class

> Explores Convolutional Operations using Pytorch and Feature Learning from Image Markers (FLIM).

This repository is organized as follows:

- **Segmentation folder:** 3 Jupyter notebooks exploring UNet architectures and segment parasite eggs in microscopy images. We use a plain UNet, a FLIM-UNet, and a backpropagation-free FLIM network;
- **Classification folder:** Three Jupyter notebooks explore CNN architectures to classify healthy/unhealthy leaves. We use a plain network, a FLIM-initialized network, and a pre-trained Vgg. The third notebook enables us to project the features into a 2D space to visualize why some classes are hard to predict correctly.

All data is automatically downloaded; use a Colab or a personal computer.