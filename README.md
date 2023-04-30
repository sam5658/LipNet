# LipNet
The project is a pytorch implementation of lip net which is based on a Convlution LSTM model for lip reading.
The dataset used in the project consist of 1000 vidoes uttering random words e.g. "place white at e seven again".
## The model follows some what same architecture as for an image captioning model

![mpg](https://user-images.githubusercontent.com/101457916/235353856-4d4f2cb4-8546-4c15-9f58-8ac1e7402e63.png)

The model was trained with the following features

sequence_length = 35

batch_size = 16

bidirectional = True

learning_rate = 0.001
