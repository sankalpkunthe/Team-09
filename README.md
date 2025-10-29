# Team-09

Task-02

1. First I imported necessary libraries including numpy, mathplotlib and tensorflow.keras 

2. Next I loaded the Fashion MNIST dataset, consisting of 60000 training and 10000 test grayscale images of size 28*28

3. Pixel values are then normalized to 0 to 1 for faster training and images are reshaped to (28,28,1) to include channel dimension needed for CNN

4. Now I converted the labels into one-hot encoded form (like [0,0,1,0,0,0,0,0,0,0]) to match the output of softmax layer

5. Then I built CNN, the output gives me probabilities for each of the 10 classes

6. Trained it on the training dataset and tested it on the test dataset. Later I plotted the training, validation accuracy and loss curves to show how the model improves over epochs

7. Then I randomly displayed on image and its predicted label
