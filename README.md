# CIFAR-10 Image Classification with ResNet18

This project focuses on building an image classification model for the CIFAR-10 dataset using a modified ResNet18 architecture. The goal was to design a model that achieves high accuracy while staying under 5 million trainable parameters.

To improve performance and generalization, the model incorporates data augmentation techniques such as Mixup and CutMix, along with regular training augmentations like random cropping and flipping. The Lookahead optimizer was used on top of Adam to enhance convergence and stability.

Global unstructured pruning was applied to reduce the number of parameters by 58%, resulting in a smaller and more efficient model without sacrificing performance. The final model achieved a test accuracy of 95.86%.
