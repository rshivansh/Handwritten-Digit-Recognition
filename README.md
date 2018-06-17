# Handwritten-Digit-Recognition
A very basic project done in second year starting


Execute the following commands in a Python shell,

>>> import mnist_loader
>>> training_data, validation_data, test_data = \
... mnist_loader.load_data_wrapper()

Then 

>>> import network
>>> net = network.Network([784, 100, 10])


Then

>>> net.SGD(training_data, 30, 10, 3.0, test_data=test_data)

That is, the trained network gives us a classification rate of about 96.59 %
