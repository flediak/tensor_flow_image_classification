# tensor_flow_image_classification
A collection of IPython notebooks for image classification, using neural networks built with Tensor Flow. The notebooks can be run on Google Colab by clicking on the corresponding link in the notebooks.

### cifar10_classification.ipynb
This notebook classifies images of the CIFAR-10 dataset using 5 different neural networks. The networks are build with Tensor Flow and fitted using GPU acceleration. Finally the model performances are compared and tested for overfitting. These tests show that using convolutions of the input images
(i.e. Convolutional Neural Networks) improves the performance, but also leads to strong overfitting. The overfitting can be reduced by introducing dropout layers in the network.
