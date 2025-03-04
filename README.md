<p align="center">
  <img src="https://miro.medium.com/v2/format:webp/0*BdetXYemwXwOqNTs.jpg" alt="Description of the image">
</p>  

# CIFAR-10 Image Classification with PyTorch 
## Overview
This project focuses on building and training a convolutional neural network (CNN) to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.  
The project is implemented using PyTorch and includes the following steps:

  1. Loading and preprocessing the CIFAR-10 dataset.
  2. Building a CNN model.
  3. Training the model with and without data augmentation.
  4. Hyperparameter tuning using Optuna.
  5. Evaluating the model on the test set.

You can veiw and run this code on Kagle through this [link](https://www.kaggle.com/code/beasttitan/image-classification-with-pytorch)

## Future Work
While the current model achieves **76% accuracy** on CIFAR-10, there are several avenues for further development:
1. **Model Architecture**: Experiment with deeper networks like ResNet or DenseNet.
2. **Data Augmentation**: Add morre techniques like random cropping, and rotation .
4. **Hyperparameter Tuning**: Run the optuna study for more trials on the augmented dataset instead of the original dataset.

