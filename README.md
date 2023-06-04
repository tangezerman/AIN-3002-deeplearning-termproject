

### AIN-3002 Deep Learning Term Project

## Abstract
This notebook presents a collaborative effort between myself and @Aslid13 for the term project of the AIN-3002 Deep Learning course. The purpose of this project is to demonstrate the practical benefits of utilizing dropout regularization  for deep neural networks. We conducted experiments using three different datasets: MNIST, CIFAR10, and MNIST-Fashion. These datasets were chosen due to their varying sizes and unique challenges.

## Dependencies
For the implementation of the neural network framework in this project, Pytorch was selected. You can install PyTorch by visiting the official website: https://pytorch.org/.

## Training
We tested three different network architectures and selected the best performing one to evaluate the effects of dropout regularization. In order to ensure reproducibility, we set the seed using `torch.manual_seed()`. It is not recommended to modify the number of epochs and batch size hyperparameters, as during testing, we observed that altering these values could result in significantly reduced accuracy.

## Evaluation
In all experiments, models trained with dropout regularization outperformed those without dropout. However, the impact of the dropout rate, as well as the degree of improvement, varied. In some cases, the effects of dropout rate were negligible, while in others, they were substantial.
