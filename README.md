Two AI models built to recognize up to 9 different trash types. Thanks to Suman Kunwar & thierrytheg for the dataset at https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2
 1. A custom built CNN model
 2. A transfer-learned model based on MobileNetV2

Note: The Keras model shown is a 71% accuracy model that's performed the best. The research paper does not mention this as it was trained later on.
Usage: Using the keras model given requires the images to be compressed to 16x16 pixels before have and for it to be in a (blue, green, red) format. I did the translation with opencv
