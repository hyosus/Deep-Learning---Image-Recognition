# Image Classification using CNN
In this assignment, I explore and compare two convolutional neural network models for image classification of 10 food types. First model will be built from scratch while the second model will be built with the use of VGG16 pre-trained model.

### Summary
Model 2 performed well, achieving 70% accuracy with small parameters and no extra layers and gradually increasing to 80%. Despite its larger loss, it was able to correctly and accurately predict all internet images. For the most part, I believe it was able to quickly classify the images using colours.

Some suggestions for future improvements include experimenting with picture augmentation, as I did not focus on fine tuning it. I may perhaps increase the rotation, including vertical flip, and brightness, exposing the model to a larger range of object distortions. If allowed, I would also add more data to the dataset as it is one of the easiest ways to increase validation accuracy. I would also increase the image size to 224 x 224 since it is a common size to VGG16, however my computer does not have the computational power to do so.
