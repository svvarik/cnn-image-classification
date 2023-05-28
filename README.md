# Image Classification using Convolutional Neural Networks

This was an assignment involving convolutional neural networks for a Computer Vision course.

As specified in the assignment, I made use of this starter code, linked [here](https://jovian.ml/ankitvashisht12/dog-breed-classifier-final/v/7?utm_source=embed). 

Also, I used a subset of data from these two datasets: 

- [Standford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)
- [Kaggle Dog Breed Identification Dataset](https://www.kaggle.com/competitions/dog-breed-identification)


### Implementing CNN

Given specifications, I implemented a CNN using PyTorch. 

### Training ResNet-18 Model 

Using the ResNet-18 model imported from PyTorch, I trained it on my data to classify the different dogs by breed. 

### Finetuning Pre-trained models

I imported the ResNet-18 model, the ResNet-34 model, and the ResNeXt-32 model with pre-trained weights. I finetuned them on the data by freezing the layers of the network, except the output layers. These models all performed remarkably well, with the ResNeXt32 model being the most accurate. 

### Limitations

The dataset I used (as specified by the assignment), was only a subset of the larger datasets. Therefore, the models didn't have as many images to learn from, and this likely impacted accuracy of my custom CNN and even the trained ResNet34 model. 
