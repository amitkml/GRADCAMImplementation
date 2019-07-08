# GRADCAMImplementation
This notebook shows how we can apply gradcam on misclassified images. Have used an pretrained model and then trained the model for some epochs before predicting.

# What is Convolutional Neural Network (CNN)?
Convolutional Neural Network
– Feed-forward artificial neural network
– Convolutional networks were inspired by biological processes
## Convolution Network Contains
– Convolution layers with activation function
– Pooling layers
– Fully connected layers
## Why Visualization in CNN?
- Each neuron/filter in a CNN is responsible for detecting a particular feature.
- In lower layers, they are responsible for detecting features such as edges,colours etc. while progressively higher layers detect complex  eatures such as object locations.
- The features detected by the later layers are more discriminative in nature making separation into various classes easier.
- Get intuitions of what makes the model behave certain way
- Helps in tweaking the hyper parameters
## Approaches for Visualization
- Class Activation Map
- Gradient-Class Activation Map
- Activation map
- Deconvolution

### Gradient Based Approach: Grad-CAM
- Uses the gradients of any target concept,flowing into the final convolutional layer to produce a coarse localization map
- highlights the important regions in the image for predicting the concept
- To establish trust in predictions from deep networks

