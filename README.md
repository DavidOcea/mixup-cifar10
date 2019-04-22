# mixup-cifar10
## Reprint only for learning, Original address：https://github.com/facebookresearch/mixup-cifar10
## Introduction：
Mixup is a generic and straightforward data augmentation principle. In essence, mixup trains a neural network on convex combinations of pairs of examples and their labels. By doing so, mixup regularizes the neural network to favor simple linear behavior in-between training examples
## Requirements and Installation：
.A computer running macOS or Linux
.For training new models, you'll also need a NVIDIA GPU and NCCL
.Python version 3.6
.A PyTorch installation
## Training:
Use python train.py to train a new model. Here is an example setting:
"$ CUDA_VISIBLE_DEVICES=0 python train.py --lr=0.1 --seed=20170922 --decay=1e-4"
