Cat and Dog classification
---------------------------
Keras Image Classification as tensorflow as backend

Classifies an image as containing either a dog or a cat (using Kaggle's public dataset), but could easily be extended to other image classification problems.

To run these scripts/notebooks, you must have keras, numpy, scipy, and h5py installed.

dog_cat_keras.py
----------------

It loads the training data and categoroizes it into cats and dogs. Then the model is built and trained and saved ase model.h5 and model.json

test_pre.py
------------

The image is loaded and tested. It will categorize the image into cat or dog category.
