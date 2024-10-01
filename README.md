# Cat-Dog-Classifier
Cat-Dog Classifier using Convolutional Neural Networks (CNN)

This repository provides a Cat-Dog classifier implemented using Convolutional Neural Networks (CNN). The project demonstrates two different approaches:

Basic CNN Architecture: A custom CNN model is built from scratch with layers for convolution, pooling, and dense connections to classify images of cats and dogs. This approach serves as an introduction to CNNs and demonstrates how to train a network with basic layers.

Transfer Learning with VGG16: The well-known VGG16 model pre-trained on ImageNet is used for transfer learning. The model’s architecture is leveraged by unfreezing the last few layers and fine-tuning it to classify cats and dogs. This approach highlights how pre-trained models can be adapted for specific tasks, saving training time and improving accuracy.

# Features
Basic CNN Model: Implementation of a CNN with a sequential architecture, including convolutional, pooling, and dense layers.

Transfer Learning with VGG16: The final layers of VGG16 are modified, and selective layers are unfrozen for fine-tuning.

Model Comparison: Evaluation of the performance of both models, demonstrating the effectiveness of transfer learning.


# Results
The transfer learning approach using VGG16 achieved higher accuracy compared to the basic CNN architecture, demonstrating the advantage of leveraging pre-trained models.

