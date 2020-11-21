# FaceMaskDetect
Welcome to Francesco, a machine learning face mask detection system that uses a software stack in python, Tensorflow, Keras API and OpenCV! Francesco can also be applied on many embedded systems as it also uses MobileNet: Efficient Convolutional Neural Networks for Mobile Vision Applications.

The main concept that francesco uses is that of a convolutional neural network, or CNN for short, a neural network that uses convolution, usually for analyzing images. It starts by applying filters that can help distill some features of the image using different kernels. These filters can be improved in the same way as other weights in the neural network, by adjusting their kernels based on the error of the output. Then, the resulting images are pooled, after which the pixels are fed to a traditional neural network as inputs (a process called flattening).

It then feeds the model into openCV where it uses my laptop's webcam (or any camera attached to the main program for that matter) to detect whether a person is wearing a mask or not in real time!

[I hope you enjoy the demo!](https://youtu.be/emdcdljuGRg)

