# CS484 Final Project

In this project, we explore the topic of weakly supervised semantic segmentation (WSSS) with image level labels. We use much of the same methodology in dataset construction, training and validation as in assignment 5. However, compared to fully supervised semantic segmentation, training on only image labels is much more difficult as there is no ground truth segmentation mask to compare with. In this project, we mainly explore different loss functions for WSSS, but also consider other factors such as hyperparameters and the model architecture itself.

For the neural network, we use a pretrained backbone from DinoV3 and add convolutional and fully connected layers to it for classification. The model will be trained on the Pascal VOC 2012 dataset.

## Libraries Used
- Torch, TorchVision, TorchMetrics: used for constructing and training the neural network
- MatPlotLib: used for visualizing results
- NumPy: used for various calculations
- PIL: used to colourize the segmentation mask
- dotenv: secure storage of variables

these can all be installed by running the command
```
pip install requirements.txt
```
