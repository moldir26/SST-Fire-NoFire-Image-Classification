# SST-Fire-NoFire-Image-Classification

We have chosen pre-trained Image Classification Model - VGG16. We did not chose Object Detection Model since it is a binary problem that doesn't need the exact location of fire. The code is .ipynb file, it was easy to use for collaboration of our team.

VGG16 is a type of CNN (Convolutional Neural Network) that is considered to be one of the best computer vision models to date. 

Here is the model arcitecture:
![vgg16](https://user-images.githubusercontent.com/100854733/202907194-c232d02b-3cbf-4d3e-aefe-ddc43b474963.jpg)

![vgg16_](https://user-images.githubusercontent.com/100854733/202907240-a16ad3aa-d9cb-4241-89dc-805ed5adc798.jpg)

(retrieved from https://medium.com/@mygreatlearning/everything-you-need-to-know-about-vgg16-7315defb5918#:~:text=VGG16%20is%20object%20detection%20and,to%20use%20with%20transfer%20learning.)

- The 16 in VGG16 refers to 16 layers that have weights. In VGG16 there are thirteen convolutional layers, five Max Pooling layers, and three Dense layers which sum up to 21 layers but it has only sixteen weight layers i.e., learnable parameters layer.
- VGG16 takes input tensor size as 224, 244 with 3 RGB channel
- Most unique thing about VGG16 is that instead of having a large number of hyper-parameters they focused on having convolution layers of 3x3 filter with stride 1 and always used the same padding and maxpool layer of 2x2 filter of stride 2.
