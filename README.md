# Transfer-Learning-using-RESNET50

ResNet, ResNetV2, ResNeXt models, with weights pre-trained on ImageNet.

This model and can be built both with 'channels_first' data format (channels, height, width) or 'channels_last' data format (height, width, channels).

The default input size for this model is 224x224.

### Arguments

### include_top: whether to include the fully-connected layer at the top of the network.
### weights: one of None (random initialization) or 'imagenet' (pre-training on ImageNet).
### input_tensor: optional Keras tensor (i.e. output of layers.Input()) to use as image input for the model.
### input_shape: optional shape tuple, only to be specified if include_top is False (otherwise the input shape has to be (224, 224, 3) (with 'channels_last' data format) or (3, 224, 224) (with 'channels_first' data format). It should have exactly 3 inputs channels, and width and height should be no smaller than 32. E.g. (200, 200, 3) would be one valid value.
### pooling: Optional pooling mode for feature extraction when include_top is False.
### None means that the output of the model will be the 4D tensor output of the last convolutional layer.
### 'avg' means that global average pooling will be applied to the output of the last convolutional layer, and thus the output of the model will be a 2D tensor.
### 'max' means that global max pooling will be applied.
### classes: optional number of classes to classify images into, only to be specified if include_top is True, and if no weights argument is specified.
## Returns--

A Keras Model instance.

# You can upload the images on google colab using google drive by importing them.
