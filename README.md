# Chainer-squeezenet
## squeezenet

SqueezeNet achieves AlexNet-level accuracy on ImageNet with 50x fewer parameters. Additionally, with model compression techniques we are able to compress SqueezeNet to less than 0.5MB

I implemented the squeezenet with Chainer and fine-tuned it
The data set is part of imagenet (it can be adjusted as needed)

Picture shape(224,224,3)

In order to solve the problem with large data sets, the LabeledImageDataset is used,and in order to be able to adjust the shape of the 
images, some modifications have been made to the source code of the LabeledImageDataset.

Lenet network for testing



SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size
https://arxiv.org/abs/1602.07360


