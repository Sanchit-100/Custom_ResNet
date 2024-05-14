# Custom ResNet
## Description
This is a simple ML ResNet model trained on the CIFAR-10 dataset.
The training is done using the PyTorch framework.

CIFAR-10 is an image dataset of 10 common objects/beings with labels.
1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

![images](https://github.com/Sanchit-100/Custom_ResNet/assets/141770981/c61c2d2b-3625-4785-8427-ba1018141467)

## Model Architecture
The architecture and training is as follows:-
<br/>
1. 4 ResNet layers each consisting of 2 Convolutional and 2 Batch Norm sub_layers.
2. ReLu activation function is chosen.
3. Adaptive Average pooling was used.

## Training

1. The train-test split was kept to be 0.8.
2. The ResNet model was tarined on 10 epochs.
3. Loss function was chosen to be CrossEntropyLoss.
4. The optimiser was Adam and learning rate is set at 0.001.

## Results
1. The model gave an accuracy of 82.77 % on the test set.
   
   ![image](https://github.com/Sanchit-100/Custom_ResNet/assets/141770981/19fd8716-1d58-49a1-af00-86b646fe9929)

2. On further increasing the number of layers to 5, the accuracy increased to 83.70 %.

   ![image](https://github.com/Sanchit-100/Custom_ResNet/assets/141770981/295e21ff-12e8-4d28-ada6-93625461a6a5)
 
