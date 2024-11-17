# dog_breed_classifier

Classification model trained from https://www.kaggle.com/datasets/gpiosenka/70-dog-breedsimage-data-set/code

Originally, I sought to build a model directly from scratch but as it turned out 9000 images just isn't enough for that, which resulted in my decision to making a customization based off of ResNet. That code is in model.ipynb. To predict using this model, add images of dogs to a subdirectory called "dogbreeds/" and use prediction.ipynb.