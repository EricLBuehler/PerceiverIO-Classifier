# PerceiverIO-Classifier
## About
This a PercieverIO based classifier. By epoch 1, it achieves 97% accuracy and a test loss of 0.005.
It has been trained on the MNIST dataset. This model is built with Pytorch.

## PercieverIO
The PercieverIO used in this model is lucidrains's implemenation, found at https://github.com/lucidrains/perceiver-pytorch.

## Training
The model was trained for 50 epochs. I used MSE (Mean Squared Error) loss for the criterion, an Adam optimizer (lr = 0.0001), and an ExponentialLR schedular with a gamma of 0.9.

Below is an example of a test after epoch 1:
![](images/image_epoch_1.png)

Accuracy, and test/train loss plots are provided below:







