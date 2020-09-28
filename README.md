## petClassificationCNN

I have used simple data augmentation to create more samples from a very little amount of images.

I have build the CNN model and the Architecture is as follows:

    Input layer 

    Convolutional layer 1 with 32 filters of kernel size[3, 3] 
    Pooling layer 1 with pool size[2,2] and stride 2 

    Convolutional layer 2 with 64 filters of kernel size[3, 3] 
    Pooling layer 2 with pool size[2,2] and stride 2 

    Flattening the Input 

    Dense layer with 64 nodes, activation 'ReLU' dropout = 0.2

    Dense layer with 32 nodes, activation 'ReLU' dropout = 0.4

    Output layer with 1 node, activation 'Sigmoid'

Please do comment and let me know incase if you feel any chages to be done to make the model perform better.

Thanks
