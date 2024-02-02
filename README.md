This project is a basic CNN that uses a LeNet-5 architecture to analyze the miniplaces dataset
It has the following layers:
Convoluted layer: kernel size= 5, Number of output channels=6, stride=1, followed by a reLu activation, followed by a 2D max pooling layer of K=2,S=2
Convoluted layer: 16 output channels, k=5, s=1, followed by a relu activation, followed by a 2d max pooling layer
flatenning layer to convert 3D tensor to 1D tensor
Linear layer with output dim 256
Linear layer with output dim 128
Linear layer with output dim 100 (Number of classes)


