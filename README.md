# DamageMap

This repository contains the code used to create and evaluate the model described in the paper **DamageMap: A post-wildfire damaged buildings classifier**.


## Codes
In the folder "code files" one can find the following jupyter notebooks:

1. "create_input_images.py": This script  creates square cropped training images from large GeoTiffs (xBD, Camp Fire or Carr Fire). 

1. "Data Augmentation.ipynb": This notebook can be used on an imbalanced dataset to perform the data augmentation techniques discussed in the paper.

1. "Train Models.ipynb": This is the notebook used to train the models discussed in the paper. One can use it to train their own models on any dataset of their choice.

1. "Use Model on New Dataset.ipynb": With this notebook, one can load a model and use it to classify the images of a new dataset.

1. "Visualize the performance of the model.ipynb": This notebook can help someone understand better the quality (and potential problems) of the predictions of a model on a given dataset.

## Models
In the folder "models and checkpoints" one can find some of the models discussed in the paper ready for use (due to space limitations some other models were not uploaded). Moreover, this folder contains some checkpoint files ("Train Models.ipynb" can illustrate how to use them), that contain useful information about the models, like the optimizer used during their training, their optimal parameters for the classification task discussed in the paper, and their validation accuracy on the Xbd validation set.
