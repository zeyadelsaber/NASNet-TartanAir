# NASNet-Large Transfer Learning — TartanAir

MATLAB NASNet-Large transfer-learning pipeline for **Nature**, **Rural**, and **Urban** TartanAir scene classification, including augmentation, validation, test evaluation, and confusion-matrix export.

**Test accuracy: 66.81%.**

## Run

Arrange the dataset as `data/{Training,Validation,Test}/{Nature,Rural,Urban}` or set `TARTANAIR_DATASET_ROOT`, then run `train_nasnet`.

Requires Deep Learning Toolbox, Computer Vision Toolbox, and the NASNet-Large support package. Generated models and the dataset are excluded from Git.

Author: [Zeyad Elsaber](https://github.com/zeyadelsaber), University of Rome Tor Vergata.
