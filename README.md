# Transfer-Learning
Flowers Identification using keras by transfer learning

# Description
This is a Multiclass Kaggle competition for identifying five different types of flowers. The dataset contain 4242 images of 5 different types of flowers namely : Roses, dandelion, Tulip, Daisy, Sunflower.

# Approach
In this, we use a technique called Transfer Learning to identify the different types of flowers.

# Transfer Learning
Transfer learning is a technique in machine learning, in which we use the pre-trained models for prediction. We can freeze the top layers of the pre-trained models like Resnet50, VGG16, etc and can add our own layers above it and make our model to train and we can use the model for prediction.

This technique is extremely useful if we have very little data to train, and we can also use another technique called 
" Data Augmentation " in ImageGenerator class provided by keras, in which the data will be looped over in batches. 
