# CNN for Image Classification on MNIST Dataset
This CNN is created to classify the handwritten images of digits 0-9 in the MNIST dataset. The neural network is defined to identify the handwritten digits into 10 classes. 
I/P :- MNIST dataset. 
O/P :- 10 classes.

## MNIST dataset 
MNIST is a dataset of handwritten digits from 0-9.

![image](https://github.com/ShikhaERAV2/ERAV2Session5/assets/160948226/d39c09bd-f820-4ae3-8c4c-6613e6c9b949)


## Model Description
This is a 4 layers Convolutional Neural Network for digits identification trained on MNIST dataset. 

## Code Structure 
- `S5_Shikha.ipynb`: The main Jupyter Notebook contains the code to load data in train and test datasets -> transform data-> load model (defined in model.py)-> train  model -> test the model -> Check the accuracy of the model thus trained. 
- `model.py`: This file contains the definition of the model. Basic architecture of the model is defined with 4 convolution layers and 2 fully connected layers. 
- `utils.py`: This file contains the utility functions like display of the sample data images and plotting the accuracy and loss during training. 

## Requirements
- Pytorch
- Matplotlib

## Model Accuracy
- Accuracy=97.29 %
- Average loss: 0.0459
- epochs = 5

  ![image](https://github.com/ShikhaERAV2/ERAV2Session5/assets/160948226/118d9fce-28fa-4814-9f17-a511a46e87f9)


