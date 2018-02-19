# Bangla-Digit-Recognition-Using-CNN


This project aim to recognize bangla handwritten digit .I use motion-blur image from offline bangla .
This dataset contain -

* train_x	193890x784 double (containing 193890 training samples of 28x28 images each linearized into a 1x784 linear vector)

* train_y	193890x10 double (containing 1x10 vectors having labels for the 193890 training samples)

* test_x	3999x784 double (containing 3999 test samples of 28x28 images each linearized into a 1x784 linear vector)

* test_y	3999x10 double (containing 1x10 vectors having labels for the 3999 test samples)



You can find tthis data set here -> http://csc.lsu.edu/~saikat/noisy-bangla

I use two convolution layers with pooling in between them, then densely connected layer(fully-connected layer) followed by dropout and lastly readout layer(softmax layer).
