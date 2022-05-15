# Adapting AlexNet architecture to CIFAR10
The goal of this project was to build the AlexNet architecture and train it on the CIFAR10 dataset.

Resizing of some of the kernel sizes and the number of kernels was considered because CIFAR10 has a smaller dataset than ImageNet, as well as lower-resolution (32x32 vs 224x224).

The number of kernels used per layer was also resized to speed up training and/or preserve accuracy.

Training, validation and test errors were reported, and hyperparameters that improved performance were also noted.

Training and validation performances were monitored using TensorBoard, and the log files are included.
