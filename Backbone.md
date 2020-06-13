https://docs.google.com/spreadsheets/d/15H_7U2f410hnoP8cLz57I7Y1M4aaXn3F4iIskYBrNwM/edit?usp=sharing
# Paper
|   |  |  |  |  |
| --- | --- | --- | --- | --- |
|  AlexNet | Imagenet classification with deep convolutional neural networks | 2012-NIPS | [paper](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks "paper") |  |
|  ZF | Visualizing and Understanding Convolutional Networks | 2014-ECCV | [arxiv](https://arxiv.org/abs/1311.2901 "arxiv") |  |
|  OverFeat | OverFeat: Integrated Recognition, Localization and Detection using Convolutional Networks | 2014-ICLR | [arxiv](https://arxiv.org/abs/1312.6229 "arxiv") |  |
|  VGG | Very deep convolutional networks for large-scale image recognition | 2015-ICLR | [arxiv](https://arxiv.org/abs/1409.1556 "arxiv") |  |
|  Inception v1 | Going Deeper with Convolutions | 2015-CVPR | [arxiv](https://arxiv.org/abs/1409.4842 "arxiv") |  |
|  Inception v2 | Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift | 2015-ICML | [arxiv](https://arxiv.org/abs/1502.03167 "arxiv") |  |
|  Inception v3 | Rethinking the Inception Architecture for Computer Vision | 2016-CVPR | [arxiv](https://arxiv.org/abs/1512.00567 "arxiv") |  |
|  Inception v4 | Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning | 2017-AAAI | [arxiv](https://arxiv.org/abs/1602.07261 "arxiv") |  |
|  ResNet,ORU | deep residual learning for image recognition | 2016-CVPR | [arxiv](https://arxiv.org/abs/1512.03385 "arxiv") | [code](https://github.com/KaimingHe/deep-residual-networks "code") |
|  ResNet,PRU | Identity Mappings in Deep Residual Networks | 2016-ECCV | [arxiv](https://arxiv.org/abs/1603.05027 "arxiv") | [code](https://github.com/KaimingHe/resnet-1k-layers "code") |
|  ResNeXt | Aggregated Residual Transformations for Deep Neural Networks | 2017-CVPR | [arxiv](https://arxiv.org/abs/1611.05431 "arxiv") | [code](https://github.com/facebookresearch/ResNeXt "code") |
|  DenseNet | Densely Connected Convolutional Networks | 2017-CVPR | [arxiv](https://arxiv.org/abs/1608.06993 "arxiv") | [code](https://github.com/liuzhuang13/DenseNet "code") |

# Leadboard
|   |  |  |  |  |  |  | ILSVRC2012 |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | --- |
|   | params | FLOPs | size | augmentation | model | crops | top1 | top5 |
|  DenseNet-121 |  |  |  |  | 1 | 1 | 25.02 | 7.71 |
|  DenseNet-169 |  |  |  |  | 1 | 1 | 23.8 | 6.85 |
|  DenseNet-201 |  |  |  |  | 1 | 1 | 22.58 | 6.34 |
|  DenseNet-264 |  |  |  |  | 1 | 1 | 22.15 | 6.12 |
|  DenseNet-121 |  |  |  |  | 1 | 10 | 23.61 | 6.66 |
|  DenseNet-169 |  |  |  |  | 1 | 10 | 22.08 | 5.92 |
|  DenseNet-201 |  |  |  |  | 1 | 10 | 21.46 | 5.54 |
|  DenseNet-264 |  |  |  |  | 1 | 10 | 20.8 | 5.29 |
|  ResNeXt-50 |  |  | 224 |  | 1 | 1 | 24.4 | 6.6 |
|  ResNeXt-101 |  |  | 224 |  | 1 | 1 | 22.2 | 5.7 |
|  Inception-ResNet-v4 |  |  |  |  | 1 | 1 | 21.3 | 5.5 |
|  Inception-v4 |  |  |  |  | 1 | 1 | 20 | 5 |
|  Inception-ResNet-v2 |  |  |  |  | 1 | 1 | 19.9 | 4.9 |
|  Inception-ResNet-v1 |  |  |  |  | 1 | 12 | 19.8 | 4.6 |
|  Inception-v4 |  |  |  |  | 1 | 12 | 18.7 | 4.2 |
|  Inception-ResNet-v2 |  |  |  |  | 1 | 12 | 18.7 | 4.1 |
|  Inception-ResNet-v1 |  |  |  |  | 1 | 144 | 18.8 | 4.3 |
|  Inception-v4 |  |  |  |  | 1 | 144 | 17.7 | 3.8 |
|  Inception-ResNet-v2 |  |  |  |  | 1 | 144 | 17.8 | 3.7 |
|  Inception-v4 +3× Inception-ResNet-v2 |  |  |  |  | 4 | 144 | 16.5 | 3.1 |
|  Resnet-50,ORU |  |  |  |  | 1 |  | 20.74 | 5.25 |
|  Resnet-101,ORU |  |  |  |  | 1 |  | 19.87 | 4.6 |
|  Resnet-152,ORU |  | 11.3b |  |  | 1 |  | 19.38 | 4.49 |
|  ResNet-152, ORU |  |  | 224/224 | scale | 1 |  | 23 | 6.7 |
|  ResNet-152, ORU |  |  | 224/320 | scale | 1 |  | 21.3 | 5.5 |
|  ResNet-152, PRU |  |  | 224/320 | scale | 1 |  | 21.1 | 5.5 |
|  ResNet-200, ORU |  |  | 224/320 | scale | 1 |  | 21.8 | 6 |
|  ResNet-200, PRU |  |  | 224/320 | scale | 1 |  | 20.7 | 5.3 |
|  ResNet-200, PRU |  |  | 224/320 | scale,asp ratio | 1 |  | 20.1 | 4.8 |
|  Inception-v3 |  |  | 299 |  | 1 | 12 | 19.47 | 4.48 |
|  Inception-v3 |  |  | 299 |  | 1 | 144 | 18.77 | 4.2 |
|  Inception-v3 |  |  | 299 |  | 4 | 144 | 17.2 | 3.58 |
|  Inception-v2 |  |  |  |  | 1 | 1 | 25.2 | 7.82 |
|  Inception-v2 |  |  |  |  | 1 | 144 | 21.99 | 5.82 |
|  Inception-v2 |  |  |  |  | 6 | 144 | 20.1 | 4.9 |
|  Inception-v1 |  |  | 224 |  | 1 | 1 |  | 10.07 |
|  Inception-v1 |  |  | 224 |  | 1 | 10 |  | 9.15 |
|  Inception-v1 |  |  | 224 |  | 1 | 144 |  | 7.89 |
|  Inception-v1 |  |  | 224 |  | 7 | 1 |  | 8.09 |
|  Inception-v1 |  |  | 224 |  | 7 | 10 |  | 7.62 |
|  Inception-v1 |  |  | 224 |  | 7 | 144 |  | 6.67 |
|  VGG-16 |  |  | 256 |  |  |  | 27 | 8.8 |
|  VGG-16 |  |  | 384 |  |  |  | 26.8 | 8.7 |
|  VGG-16 |  |  | [256;512]/384 |  |  |  | 25.6 | 8.1 |
|  VGG-16 |  |  | 256/[224;256;288] |  |  |  | 26.6 | 8.6 |
|  VGG-16 |  |  | 384/[352;384;416] |  |  |  | 26.5 | 8.6 |
|  VGG-16 |  |  | [256;512]/[256;384;512] |  |  |  | 26.5 | 7.5 |
|  VGG-16 |  |  |  |  |  |  | 24.6 | 7.5 |
|  VGG-16 |  |  |  |  |  |  | 24.4 | 7.2 |
|  VGG-19 |  |  | 256 |  |  |  | 27.3 | 9 |
|  VGG-19 |  |  | 384 |  |  |  | 26.9 | 8.7 |
|  VGG-19 |  |  | [256;512]/384 |  |  |  | 25.5 | 8 |
|  VGG-19 |  |  | 256/[224;256;288] |  |  |  | 26.9 | 8.7 |
|  VGG-19 |  |  | 384/[352;384;416] |  |  |  | 26.7 | 8.6 |
|  VGG-19 |  |  | [256;512]/[256;384;512] |  |  |  | 24.8 | 7.5 |
|  VGG-19 |  |  |  |  |  |  | 24.6 | 7.4 |
|  VGG-19 |  |  |  |  |  |  | 24.4 | 7.1 |


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MTYzNzgzMDgsLTE3NTY5MzMyNTEsMj
A3NzgwMDY5Niw3MzA5OTgxMTZdfQ==
-->