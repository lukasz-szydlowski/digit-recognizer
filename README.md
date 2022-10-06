# Digit Recognizer

This is my very first neural network I designed on my own after I completed several ML, TensorFlow and Python courses. I tempted to go with the easiest approach and use network with only fully connected Dense layers. The training images seemed to be very clear and easy to uplift by such architecture. However I eventually decided to use more sophisticated units to try out what I had learnt so far. The network is built up from 2 blocks of Conv2D layers with MaxPool2Ds and Dropouts followed by classifier block with 10 outputs and SoftMax as activation function. Classic architecture for those kind of problems worked very well for me giving an high accuracy of 0.9921.

[Link to the project in Colab](https://github.com/lukaszszydlowski/digit-recognizer/blob/main/Digit_Recognizer.ipynb)
